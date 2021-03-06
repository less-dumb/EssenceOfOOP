# EssenceOfOOP

[velog](https://velog.io/@urtimeislimited/%EA%B0%9D%EC%B2%B4%EC%A7%80%ED%96%A5%EC%9D%98-%EC%82%AC%EC%8B%A4%EA%B3%BC-%EC%98%A4%ED%95%B4)
### 출처
***
[객체지향의 사실과 오해](http://www.yes24.com/Product/Goods/18249021)


### 1. 협력하는 객체들의 공동체
#### 역할과 책임
- 여러 사람이 동일한 역할을 수행할 수 있습니다.
- 역할은 대체 가능성을 의미합니다.
- 책임을 수행하는 방법은 자율적으로 선택할 수 있습니다.
- 한 사람이 동시에 여러 역할을 수행할 수 있다.
#### 역할, 책임, 협력
__기능을 구현하기 위해서 협력하는 객체들__
__"어떠한 객체도 섬이 아니다."__

객체라는 공동체 안에 살고 있는 성실한 객체 시민은 자신에게 주어진 역할과 책임을 다하는 동시에 시스템의 더 큰 목적을 이루기 위해 다른 객체와도 적극적으로 협력합니다.
애플리케이션의 기능은 더 작은 책임으로 분할되고, 책임은 적절한 역할을 수행할 수 있는 객체의 의해 수행됩니다. 시스템의 기능은 객체 간의 연쇄적인 요청과 응답의 흐름으로 구성된 협력으로 구현됩니다.

#### 역할은 관련성 높은 책임의 집합이다.
- 여러 객체가 동일한 역할을 수행할 수 있다.
- 역할은 대체 가능성을 의미한다.
- 각 객체는 책임을 수행하는 방법을 자율적으로 선택할 수 있다.
- 하나의 객체가 동시에 여러 역할을 수행할 수 있다.
역할은 유연하고 재사용 가능한 협력관계를 구축하는데 중요한 설계 요소입니다. 대체가능한 역할과 책임은 객체지향 패러다임의 중요한 기반을 제공하는 다형성과도 깊이 연관되어 있습니다.

#### 협력 속에 사는 객체
협력 공동체의 일원으로서 객체는 다음과 같은 두 가지 덕목을 갖춰야 하며, 두 덕목 사이에서 균형을 유지해야 합니다.

1. 객체는 충분히 '협력적'이어야합니다.
객체는 다른 객체의 요청에 충실히 귀 기울이고 다른 객체에게 적극적으로 도움을 요청할 정도로 열린 마음을 지녀야 합니다. __객체는 다른 객체의 명령에 복종하는 것이 아니라 요청에 응답할 뿐입니다. 어떤 방식으로 응답할지는 객체 스스로 판단하고 결정하며 심지어 요청에 응할지 여부도 객체 스스로 결정할 수 있습니다.
2. 객체가 충분히 '자율적'이어야 합니다. 요청에 따른 행동은 객체 스스로가 판단해야 합니다.

#### 상태와 행동을 함께 지닌 자율적인 객체

흔히 객체를 상태와 행동을 함께 지닌 실체라고 정의합니다.
이 말은 객체가 협력에 참여하기 위해 어떤 행동을 해야한다면 그 행동을 하는데 필요한 상태도 함께 지니고 있어야 한다는 것을 의미합니다. 객체가 협력에 참여하는 과정 속에서 스스로 판단하고 스스로 결정하는 자율적인 존재로 남기 위해서는 필요한 행동과 상태를 함께 지니고 있어야 합니다.

객체의 자율성은 객체의 내부와 외부를 명확하게 구분하는 것으로부터 나옵니다.
객체의 사적인 부분은 객체 스스로 관리하고 외부에서는 일체 간섭할 수 없도록 차단해야 하며 객체의 외부에서 접근이 허락된 수단을 통해서만 객체와의 의사소통을 해야합니다.

__객체는 다른 객체가 무엇(what)을 수행하는지는 알수 있지만 '어떻게(how)' 수행하는지에 대해서는 알 수 없습니다.__ 따라서 객체는 상태와 행위를 하나의 단위로 묶는 자율적인 존재입니다. 과거 전통적인 개발 방법은 데이터와 프로세스를 엄격하게 구분합니다. 이에 반해 __객체지향에서는 데이터와 프로세스를 객체라는 하나의 틀 안에서 함께 묶어 놓음으로써 객체의 자율성을 보장합니다.__ 이것이 전통적인 개발 방법과 객체지향을 구분짓는 가장 핵심적인 차이입니다.
 
> #### 객체지향의 본질
- 객체지향이란 __"시스템"을 상호작용하는 자율적인 객체들의 "공동체"__로 바라보고 __"객체"를 이용해 시스템을 "분할"하는 방법__입니다.
- __"자율적인 객체"란 "상태"와 "행위"를 함께 지니며 스스로 "자기 자신을 책임"지는 객체를 의미__합니다.
- __"객체"는 "시스템의 행위를 구현"하기 위해 "다른 객체와 협력"합니다.__
각 객체는 "협력" 내에서 "정해진 역할을 수행"하며 "역할"은 "관련된 책임의 집합"입니다.
- 객체는 __다른 객체와 협력하기 위해 메시지를 "전송"__하고, __메시지를 수신한 객체는 메시지를 처리하는 데 적합한 메서드를 자율적으로 "선택"__한다.
- __객체지향의 핵심은 클래스가 아닙니다__. __적절한 책임을 수행하는 역할 간의 유연하고 견고한 협력 관계를 구축하는 것입니다.__ __클래스들의 정적인 관계가 아니라 메시지를 주고받는 객체들의 동적인 관계가 상대적으로 더 중요합니다.__
- 지나치게 클래스를 강조하는 관점은 객체의 캡슐화를 저해하고 클래스를 서로 강하게 결합시키기 때문에 유연하고 확장 가능한 애플리케이션의 구축을 방해합니다.

#### 객체를 지향하라
객체지향의 핵심은 클래스가 아닙니다. 핵심은 적절한 책임을 수행하는 역할 간의 유연하고 견고한 협력 관계를 구축하는 것입니다. 객체지향 중심에는 클래스가 아니라 객체가 위치하며, 중요한 것은 __클래스들의 정적인 관계가 아니라 메시지를 주고받는 객체들의 동적인 관계입니다.__

__클래스의 구조와 메서드가 아니라 객체의 역할, 책임, 협력에 집중하세요. 객체지향은 객체를 지향하는 것이지 클래스를 지향하는 것이 아닙니다.__


***
### 2. 이상한 나라의 객체
객체지향 패러다임은 지식을 추상화하고 추상화한 지식을 객체 안에 캡슐화함으로써 실세계의 문제에 내재된 복잡성을 관리합니다. 객체를 발현하고 창조하는 것은 지식과 행동을 구조화하는 문제입니다.

#### 객체, 그리고 소프트웨어 나라
객체ㅡ이 다양한 특성을 효과적으로 설명하기 위해서는 객체를 상태(state), 행동(behavior), 식별자(identifier)를 지닌 실체로 보이는 것이 가장 효과적입니다.

#### 상태
__"왜 상태가 필요한가?"__
상태를 이용하면 과거의 모든 행동 이력을 설명하지 않고도 행동의 결과를 쉽게 예측하고 설명할 수 있습니다. 상태를 이용하면 과거에 얽매이지 않고 현재를 기반으로 객체의 행동 방식을 이해할 수 있습니다. __상태는 근본적으로 세상의 복잡성을 완화하고 인지 과부하를 줄일 수 있는 중요한 개념__입니다.

#### 행동
객체의 상태는 저절로 변경되지 않습니다. 객체의 상태를 변경하는 것은 객체의 자발적인 행동일 뿐입니다.

객체가 취하는 행동은 객체 자신의 상태를 변경시킵니다. 객체의 행동에 의해 객체의 상태가 변경된다는 것은 행동이 부수 효과를 초래한다는 것을 의미합니다.

상태와 행동 사이에는 다음과 같은 관계가 있음을 알 수 있습니다.

>
- 객체의 행동은 상태에 영향을 받는다.
- 객체의 행동은 상태를 변경 시킨다.

#### 식별자
__객체란 인간의 인지 능력을 이용해서 식별 가능한 경계를 가진 모둔 사물
--을 의미합니다. 객체가 식별 가능하다는 것은 객체를 서로 구별할 수 있는 특정한 프로퍼티가 객체 안에 존재한다는 것을 의미합니다. 모든 객체가 식별자를 가진다는 것은 반도로 객체가 아닌 단순한 값은 식별자를 가지지 않는다는 것을 의미합니다.

__상태를 이용해서 두 값이 같은지 판단할 수 있는 성질을 동등성(equality)이라고 합니다.__상태를 이용해서 동등성을 판단훌 수 있는 이유는 값의 상태가 변하지 않기 때문입니다. 값의 상태는 결코 변하지 않기 때문에 어떤 시점에 동일한 타입의 두 값이 같다면 언제까지라도 두 값은 동등한 상태를 유지할 것입니다.

식별자를 기반으로 객체가 같은지를 판단할 수 있는 성질을 동일성 이라고 합니다.

>
- 객체는 상태를 가지며 상태는 변경 가능합니다.
- __객체의 상태를 변경시키는 것은 객체의 행동입니다.__
- __행동의 결과는 상태에 의존적__이며 상태를 이용해서 서술할 수 있습니다.
- 행동의 순서가 실행 결과에 영향을 미칩니다.
- 객체는 어떤 상태에 있더라도 유일하게 __"식별"__ 가능하다.

#### 행동이 상태를 결정한다.

객체지향에 갓 입문한 사람들이 가장 쉽게 빠지는 함정은 상태를 중심으로 객체를 바라 보는 것입니다. 다음과 같은 이유로 상태를 중심으로 객체를 바라보는것이 좋지 않습니다.

- 상태를 먼저 결정할 경우 캡슐화가 저해됩니다. 상테에 초점을 맞출 경우 상태가 객체 내부로 깔끔하게 캡슐화되지 못하고 공용 인터페이스에 그대로 노출되버린 확률이 높습니다.
- 객체를 협력자가 아닌 고립된 섬으로 만듭니다. __객체가 필요한 이유는 애플리케이션의 문맥 내에서 다른 객체와 협력하기 위해서__입니다. 불행하게도 상태를 먼저 고려하는 방식은 협력이라는 문맥에서 멀리 벗어난 객체를 설계힘으로써 자연스럽게 협력에 접합하지 못하는 객체를 창조하게 됩니다.
- 재사용성이 저하됩니다. __객체의 재사용성은 다양한 협력에 참여할 수 있는 능력이 나온다.__상태에 초점을 맞추 객체는 다양한 협력에 참여하기 어렵기 때문에 재사용성이 저하될 수밖에 없다.

#### 은유와 객체
객체지향 세계는 현실 세계의 단순한 모방이 아닙니다. 소프트웨어 안에 구현된 상품 객체는 실제 세계의 상품과 전혀 다른 양상을 띕니다. 소프트웨어 상품은 실제 세계의 상품이 하지 못하는 가격 계산과 같은 행동을 스스로 수행할 수 있다. 이것은 소프트웨어 상품이 실제 세계의 상품을 단순화하거나 추상화하는 것이 아니라 특성이 전혀다른 것임을 의미한다.

#### 의인화
현실 속의 객체와 소프트웨어 객체 사이의 가장 큰 차이점은 __현실 속에서는 수동적인 존재가 소프트웨어 객체로 구현될 때는 능동적으로 변한다는 것__입니다. 소프트웨어 객체를 창조할 때 우리는 결코 현실 세계의 객체를 모방하지 않습니다. 오히려 소프트웨어 안에 창조하는 객체에게 현실 세계의 객체와 전혀 다른 특징을 부여하는 것이 일반적입니다.

***

### 3. 타입과 추상화

#### 개념의 세 가지 관점
- 심볼 : 개념을 가리키는 간략한 이름이나 명칭
- 내연 : 개념의 완전한 정의를 나타내며 내연의 의미를 이용해 객체가 개념에 속하는지 여부를 확인이 가능
- 외연 : 개념속에 속한 모든 객체의 집합

트럼프 예시

- 심볼 : 트럼프
- 내연 : 몸이 납잡하고 두 손과 두 발은 네모 귀통이에 달려 있는 등장인물
- 외연 : 정원사, 병사, 신하, 왕자와 공주, 하객으로 참석한 옹과 왕비들, 히트잭, 하트 왕과 하트 여왕


#### 타입
__"타입은 개념이다."__

#### 객체와 타입입
객체가 어떤 행동을 하느냐에 따라 객체의 타입이 결정됩니다. 객체의 타입은 객체의 내부 표현과는 아무런 상관이 없습니다. 따라서 객체의 내부 표현 방식이 다르더라도 어떤 객체들이 동일하게 행동한다면 그 객체들은 동일한 타입에 속합니다.

#### 객체와 타입
객체지향 프로그램을 작성할 때 우리는 객체를 일종의 데이터 처럼 사용합니다. 따라서 객체를 타입에 따라 분류하고 그 타입에 이름을 붙이는 것은 프로그램에서 사용할 새로운 데이터 타입을 선언하는 것과 같습니다.

__"객체는 행위에 따라 변할 수 있는 상태를 가지고 있다는 사실을 기억하라"__ 애플리케이션 내부에 살고 있는 모든 객쳋의 상태를 모으면 결국 애플리케이션에서 관리해야 하는 전체 데이터를 표현할 수 있게 됩니다.

__"객체는 데이터인가? 그렇지 않다." 다시 한번 강조하지만 객체에서 중요한 것은 객체의 행동입니다.__ 상태는 행동의 결과로 초래된 부수효과를 쉽게 표현하기 위해 도입한 추상적인 개념일 뿐입니다.

객체를 창조할 때 가장 중요하게 고려해야 하는 것은 객체가 이웃하는 객체와 협력하기 위해 어떤 행올을 해야할지를 결정하는 것입니다. 즉 객체가 협력을 위해 어떤 책임을 지녀야 하는지를 결정하는 것이 객체지향 설계의 핵심입니다.

#### 행동이 우선이다.
__객체의 내부 표현 방식이 다르더라도 어떤 객체들이 동일하게 행동한다면 그 객체들은 동일한 타입에 속합니다. 결과적으로 동일한 책임을 수행하는 일련의 객체는 동일한 타입에 속한다고 말할 수 있습니다.__

그 객체가 어떤 데이터를 가지고 있는지는 우리의 관심사가 아닙니다. 그 객체가 다른 객체와 동일한 데이터를 가지고 있더라도 다른 행동을 한다면 그 객체들은 서로 다른 타입으로 분류되어야 합니다.

결론적으로 __객체의 타입을 결정하는 것은 객체의 행동일 뿐입니다.__ 객체가 어떤 데이터를 보유하고 있는지는 타입을 결정하는데 아무런 영향도 미치지 않습니다.

훌륭한 객체지향 설계는 외부에 행동만을 제공하고 데이터는 행동 뒤로 감춰야 하며, 이 원칙을 흔히 __"캡슐화"__라고 합니다.

#### 타입의 목적
"왜 타입을 사용해야 하는가? 객체지향은 객체를 지향하는 것이므로 객체만 다루면 되지 않는가?" 타입을 사용하는 이유는 인간의 인지 능력으로는 시간에 따라 동적으로 변하는 객체의 복잡성을 극복하기가 너무 어렵기 때문입니다.

앨리스의 상태가 지속해서 변하더라도 모든 경우에 앨리스는 단지 앨리스일 뿐이다.

***
### 4. 역할, 책임, 협력
#### 협력
#### 요청하고 응답하며 협력하는 사람들#### 
혼자만의 힘으로는 해결하기 어렵기 때문에 해결 과정에서 여러 사람이 참여하게 됩니다. 이 과정 속에서 요청과 응답의 연쇄적인 흐름이 발생합니다.

협력은 한 사람이 다른 사람에게 도움을 요청할 때 시작됩니다. 자신에게 할당된 일이나 업무를 처리하던 중에 스스로 해결하기 어려운 문제에 부딪히게 되면 문제를 해결하는 데 필요한 지식을 알고 있거나 도움을 받을 수 있는 누군가에게 도움을 됩니다.

#### 재판 속의 협력 예시
- 누군가 왕에게 재판을 __"요청"__함으로써 재판이 시작된다.
- 왕이 하얀 토끼에게 증인을 부를 것을 __"요청"__한다.
- 왕의 요청을 받는 토끼는 모자 장수에게 증인석으로 입장할 것을 __"요청"__한다.
- 모자 장수는 입장은 왕이 토기에게 요청했던 증인 호출에 대한 __"응답"__이기도 하다.
- 모자 장수는 자신이 알고 있는 내용들을 증엄함으로써 왕의 요청에 __"응답"__한다.

__어떤 등장인물들이 특정한 요청을 받아들일 수 있는 이유는 그 요청에 대한 적절한 방식으로 응답하는데 필요한 지식과 행동 방식을 가지고 있기 때문입니다. 그리고 요청과 응답은 협력에 참여하는 객체가 수행할 책임을 정의합니다.__

#### 책임
객체지향의 세계에서는 어떤 객체가 어떤 요청에 대해 대답해 줄 수 있거나, 적절한 행동을 할 의무가 있는 경우 해당 객체가 책임을 가진다고 말합니다. 객체지향에서 가장 중요한 능력은 책임을 능숙하게 소프트웨어 객체에게 할당하는 것이라고도 합니다.

#### 책임의 분류
객체의 책임을 크게 "하는 것"과 "아는 것" 이라는 두 가지 범주로 자세히 분류할 수 있습니다.

__하는 것 (doing)__
- 객체를 생성하거나 계산하는 등의 스스로하는 것
- 다른 객체의 행동을 시작 시키는 것
- 다른 객체의 활동을 제어하고 조절하는 것

__아는 것 (knowing)__
- 개인적인 정보에 관해 아는것
- 관련된 객체에 관해 아는 것
- 자신이 유도하거나 계산할 수 있는 것에 관해 아는 것

#### 책임과 메세지
협력 안에서 객체는 다른 객체로부터 요청이 전송됐을 경우에만 자신에게 주어진 책임을 수행합니다.

결국 한 객체가 다른 객체에게 전송된 요청은 그 요청을 수신할 객체의 책임이 수행되도록 합니다. 이처럼 객체가 다른 객체에게 주어진 책임을 수행하도록 요청을 보내느것을 __메시지 전송 이라고 하며, 메시지는 협력을 위한 객체가 다른 객체로 접근할 수 있는 유일한 방법입니다.__

#### 역할
__"책임의 집합이 의미하는 것"__

__역할이 답이다__
재판이라는 협력 과정 속에서 하트 왕과 하트 여왕은 "판사"의 역할을 수행합니다. 모자 장수와 요리사, 그리고 엘리스는 "증인"의 역할을 수행합니다. 따라서 "판사"와 "증인"이라는 역할을 사용하면 세 가지 협력을 모두 포괄할 수 있는 하나의 협력으로 추상화됩니다.

역할은 협력 내에서 다른 객체로 대체할 수 있음을 나타내는 일종의 표식입니다. __협력 안에서 역할은 "이 자리는 해당 역할을 수핼할 수 있는 어떤 객체라도 대신할 수 있다."__ 라고 말하는 것과 같습니다.

#### 협력과 추상화
__역할의 가장 큰 가치는 하나의 협력 안에서 여려 종류의 객체가 참여할 수 있게 함으로써 협력을 추상화할 수 있다는 것입니다.)) 역할을 이용하면 협력을 추상화함으로써 단순화할 수 있다.

#### 대체 가능성
역할은 협력 안에서 구체적인 객체로 대체될 수 있는 추상적인 협력자입니다. 따라서 본질적으로 역할은 다른 객체에 의해 대체 가능함을 의미합니다.

- 객체가 역할을 대체하기 위해서는 행동이 호환되어야 한다는 점에 주목해야 합니다.
- 객체가 역할에 주어진 책임 이외에 다른 책임을 수행할 수도 있다는 사실에 주목해야 합니다.
- 역할은 대체 가능성은 행위 호환성을 의미하고, 행위 호환성은 동일한 책임의 수행을 의미합니다.

#### 객체의 모양을 결정하는 협력
#### 흔한 오류
시스템에 필요한 데이터를 저장하기 위해 객체가 존재한다는 선입견을 가질 수 있습니다. 물론 객체가 상태의 일부로 데이터를 포함하는 것은 사실이지만 데이터는 단지 객체가 행위를 수행하는 데 필요한 재료일 뿐입니다. __객체가 존재하는 이유는 행위를 수행하며 협력에 참여하기 위해서입니다. 실제 중요한 것은 객체의 행동. 즉 책임입니다.__

### 5. 책임과 메시지
#### 자율적임 책임
- 객체가 책임을 자율적으로 수행하기 위해서는 객체에게 할당되는 책임이 자율적이어야 합니다.
- 너무 추상적인 책임은 해당 책임에 협력에 참여한 의도가 명확해지지 않기 때문에 협력 의도를 뚜렷하게 표현할 수 있을 정도로 구체적이어야 합니다.

#### 어떻게가 아니라 무엇을
__자율적인 책임의 특징은 객체가 "어떻게" 해야하는가가 아니라 "무엇을" 해야하는가를 설명합니다.__

#### 메시지와 메서드
하나의 객체는 메세지를 전송함으로써 다른 객체에 접근합니다. 왕이 모자 장수에게 전송하라는 메세지를 가리키는 '증언하라'라는 메세지를 전송합니다. 하얀 토끼 역시 메시지를 전송하는 방법 이외의 다른 방법으로 모자 장수에게 접근할 수 없습니다. 이 경우에는 하얀 토끼는 송신자 모자 장수는 수신자가 됩니다.

왕이 모자 장수에게 전송하라는 메시지를 가리키는 '증언하라'라는 부분을 메시지이름(message name)이라고 합니다. 메시지를 전송할 때 추가적인 정보가 필요한 경우 메시지 인자(argument)를 통해 추가 정보를 제공할 수 있습니다.

메시지는 __메시지 이름(message name)__과 __인자(argument)__ 두 부분으로 구성됩니다. 왕이 어제 왕국에 목격한 것을 증언할 것을 요청하고 싶을때

>
증언하라(어제, 왕국)

메시지를 수신받은 객체는 우선 자신이 해당 메시지를 처리할 수 있는지 확인합니다. 메시지를 처리할 수 있다는 이야기는 객체가 해당 메시지에 해당하는 행동을 수행해야 할 책임이 있다는 것을 의미합니다. 따라서 근본적으로 메시지의 개념은 책임의 개념과 연결됩니다.

#### 다형성

__다형성__이란 서로 다른 유형의 객체가 동일한 메시지에 대해서 서로 다르게 반응하는 것을 의미합니다. 좀 더 추가적으로 말해 __서로 다른 타입에 속하는 객체들이 동일한 메시지를 수신할 경우 서로 다른 메서드를 이용해 메시지를 처리 할 수 있는 메커니즘__을 가리킨다.

__다형성은 역할, 책임, 협력과 깊은 관련이 있습니다. 서로 다른 객체들이 다형성을 만족시킨다는 것은 객체들이 동일한 책임을 공유한다는 것을 의미합니다.__

다형성에서 중요한것은 메시지 송신자의 관점입니다. 메시지 송신자의 관점에서 이 객체들이 동일한 책임을 수행한다는 것입니다. 즉 송신자의 관점에서 다형적인 수신자들을 구별할 필요가 없으며 자신의 요청을 수행할 책임을 지닌다는 점에 모두 동일합니다.

기본적으로 __다형성은 동일한 역할을 수행할 수 있는 객체들 사이의 대체 가능성을 의미합니다. 다형성은 객체들의 대체 가능성을 이용해 설계를 유연하고 재사용 가능하게 만들 수 있습니다.__ 다형성을 사용하면 송신자가 수신자의 종류를 모르더라도 메시지를 전송할 수 있습니다.

즉, __다형성은 수신자의 종류를 캡슐화합니다.__

다형성은 송신자와 수신자 간의 객체 타입에 대한 결합도를 메시지에 대한 결합도를 낮춤으로써 달성됩니다. 이것은 __객체지향이 유연하고 확장 가능하며 재사용성이 높다__는 명성을 얻게 된 배경에  다형성이라는 무기가 어떻게 작용했는지 설명하기 때문에 중요합니다.
__다형성을 사용하면 메시지를 이해할 수 있는 어떤 객체와도 협력할 수 있는 유연하고 확장 가능한 구조 설계가 가능합니다.
객체지향 패러다임이 강력한 이유는 다형성을 이용해 협력을 유연하게 만들 수 있기 때문이라는 점을 기억해야 합니다.__

#### 유연하고 확장 가능하며 재사용성이 높은 협력의 의미

송신자가 수신자에 대해 매우 적은 정보만 알고 있더라도 상호 협력이 가능하다는 사실은 설계의 품질에 큰 영향을 미칩니다.
>1. 협력이 유연해진다.
   - 송신자에 대한 파급효과 없이 유연하게 협력을 변경할 수 있습니다.
 2. 협력이 수행되는 방식을 확장할 수 있다.
    - 송신자에게 아무런 영향도 미치지 않고서도 수신자를 교체할 수 있기 때문에 협력의 세부적인 수행 방식을 쉽게 수정할 수 있습니다.
3. 협력이 수행되는 방식을 재사용할 수 있습니다.

#### 메시지를 따라라
#### What/Who 사이클
"책임-주도 설계"의 핵심은 어떤 행위가 필요한지를 먼저 결정한 후에 이 행위를 수행할 객체를 결정하는 것입니다. 이 과정을 What/Who 사이클 이라고 합니다.

What/Who 사이클 이 의미하는 것은 객체 사이의 협력 관계를 설계하기 위해서 먼저 __'어떤 행위 What'__를 수행할 것인지를 결정한 후에 누가 __'누가 Who'__그 행위를수행할 것인가를 결정해야 한다는 것입니다. 여기서 '어떤 행위'가 메시지 입니다.

객체가 어떤 메시지를 수신하고 처리할 수 있냐가 객체의 책임을 결정합니다.

#### 묻지 말고 시켜라
메시지를 먼저 결정하고 객체가 메시지를 따르게 하는 설계 방식은 객체가 외부에 제공하는 인터페이스가 독특한 스타일을 따르게 합니다. 이 스타일을 "묻지 말고 시켜라" (Tell, Don't)라고 합니다.

송신자는 수신자가 어떤 객체 인지 모르기 때문에 객체에 관해 꼬치꼬치 캐물을 수 없습니다. 단지 송신자는 수신자가 어떤 객체인지는 모르지만 자신이 전송한 메시지를 잘 처리할 것이라는 것을 믿고 메시지를 전송할 수 밖에 없습니다.

이런 스타일의 협력 패턴은 "묻지 말고 시켜라"라는 이름으로 널리 알려져 있습니다. 이 스타일은 객체지향 애플리케이션이 자율적인 객체들의 공동체라는 사실을 강조합니다. 어떤 객체가 존재하는지도 모르는데 어떻게 객체의 내부 상태를 가정할 수 있을까요?

__객체는 다른 객체의 상태를 묻지 말아야 합니다. 객체가 다른 객체의 상태를 묻는 다는 것은 메시지를 전송하기 이전에 객체가 가져야 하는 상태에 관해 너무 많이 고민 하고 있다는 증거입니다.__ 고민을 연기하고 단지 필요한 메시지를 전송하기만 하고 메시지를 수신하는 객체가 스스로 메시지의 처리 방법을 결정하게 해야 합니다.

#### 메시지를 믿어라
- 메시지를 전송하는 객체의 관점에서 자신이 전송하는 메시지를 수신할 수 있다면 협력 하는 객체의 종류가 무엇인지는 중요하지 않습니다.
  - 커피를 시켰는데 누가 주문을 받던지 상관 없이 손님은 커피를 받으면 됩니다.
- 중요한 것은 메시지를 수신한 객체가 메시지의 의미를 이해하고 메시지를 전송한 객체가 의도한 대로 요청을 처리할 수 있는 지 여부입니다.
  - 위에서 말했던 것처럼 커피만 온전히 받으면 됩니다.
- 메시지를 이해할 수 있다면 다양한 타입의 객체로 협력 대상을 자유롭게 교체할 수 있기 때문에 설계가 좀 더 유연해집니다.
  - 다형성을 말합니다.
  
#### 객체 인터페이스
#### 인터페이스
일반적으로 인터페이스란 어떤 두 사물이 마주치는 경계 지점에서 서로 상호작용 할 수 있게 이어주는 방법이나 장치를 의미합니다.

인터페이스는 다음과 같은 세 가지 특징을 지닙니다

- 인터페이스의 사용법을 익히기만 하면 내부 구조나 동작 방식을 몰라도 쉽게 대상을 조작하거나 의사를 전달 할 수 있다.
- 인터페이스 자체는 변경하지 않고 단순히 내부 구성이나 작동 방식만 변경하하는 것은 인터페이스 상용자에게 어떤 영향도 미치지 않는다.
- 대상이 변경되더라도 동일한 인터페이스를 제공하기만 하면 아무린 문제 없이 상호작용 할 수 있습니다.

#### __"인터페이스와 구현의 분리 원칙"__ (가장 중요)
#### 객체 관점에서 생각하는 방법
휼륭한 객체란 구현을 모른 채 인터페이스만 알면 쉽게 상호작용할 수 있는 객체를 의미합니다. 이 것은 객체를 설계할 때 객체 외부에 노출되는 인터페이스와 객체의 내부에 숨겨지는 구현을 명확하게 분리해서 고려해야 한다는 것을 의미합니다.

__인터페이스와 구현의 분리 원칙이 왜 중요하냐면, 그것은 소프트웨어는 항상 변경되기 때문입니다.__ 수 많은 객체들이 물고 물리며 돌아가는 객체지향 공동체에서 어떤 객체를 수정했을 때 어떤 객체가 영향을 받는지 판단하는 것은 거의 곡예에 가깝습니다.

객체가 가져야 할 상태와 메서드 구현은 객체 내부에 속합니다. 이 부분은 수정하더라도 갹체 외부에 영향을 미쳐서는 안됩니다. 객체 외부에 영향을 미치는 변경은 객체의 공용 인터페이스를 수정할 때 뿐입니다.

객체지향적인 사고 방식을 이해하기 위해서는 다음의 세 가지 원칙이 중요하다고 주장합니다.

- 좀 더 추상적인 인터페이스
- 최소 인터페이스
- 인터페이스 구현 간에 차이가 있다는 점을 인식

1. 좀 더 추상적인 인터페이스
좀 더 추상적인 인터페이스에 관해서는 자율적인 책임을 다루면서 이미 살펴봤습니다. 왕이 모자 장수에게 '목격했던 장면을 떠올려라', '떠오르는 기억을 시간 순서대로 재구성하라', '말로 간결하게 표현하라' 와 같은 지나치게 상세한 수준의 메시지를 보내는 것은 객체의 자율성을 저해합니다. 대신에 '증언하라'라는 좀 더 추상적인 수준의 메시지를 수신할 수 있는 인터페이스를 제공하면서 수신자의 자율성을 보장할 수 있습니다.

2. 최소 인터페이스
외부에서 사용할 필요가 없는 인터페이스는 최대한 노출하지 말라는 것입니다. 인터페이스를 최소로 유지하면 객체의 내부 동작에 대해 가능한 적은 정보만 외부에 노출할 수 있습니다. 따라서 객체의 내부를 수정하더라도 외부에 미치는 영향을 최소할 수 있습니다. 최소 인터페이스는 메시지를 먼저 결정하고 객체를 나중에 선택하는 책임-주도 설계 방법을 따를 때 달성할 수 있습니다.

__3.인터페이스 구현 간에 차이가 있다는 점을 인식__
__구현__
객체지향의 세계에서 내부 구조와 작동 방식을 가리키는 고유의 용어는 구현(Implementation)입니다. 객체를 구성하지만 공용 인터페이스에 포함되지 않는 것이 구현에 포함됩니다.

객체는 상태를 가집니다. 상태는 어떤 식으로든 객체에 포함되겠지만 객체 외부에 노출 되는 공용 인터페이스의 일부는 아닙니다. 따라서 상태를 어떻게 표현할 것인가는 객체의 구현에 해당합니다.

객체는 행동을 가집니다. 행동은 메시지를 수신했을 때만 실행되는 일종의 메시지 처리 방법입니다. 이 처리 방법을 메서드라 합니다. 메서드를 구성하는 코드는 자체는 객체 외부에 노출된 공용 인터페이스의 일부는 아니기 때문에 객체의 구현 부분에 포함됩니다.

__인터페이스와 구현의 분리 원칙__
__휼륭한 객체란 구현을 모른 채 인터페이스만 알면 쉽게 상호작용할 수 있는 객체__를 의미합니다. 이것은 __객체를 설계할 때 객체 외부에 노출되는 인터페이스와 객체의 내부에 숨겨지는 구현을 명확하게 분리해서 고려해야 한다는 것을 의미합니다.__

__인터페이스와 구현의 분리 원칙이  중요한 이유는 "소프트웨어의 잦은 변경" 입니다.__
객체가 가져야 할 상태와 메서드 구현은 객체 내부에 속하며 이 부분은 수정하더라도 객체 외부에 영향을 미쳐서는 안됩니다. 객체 외부에 영향을 미치는 변경은 객체의 공용 인터페이스를 수정할 때 뿐입니다.

#### 캡슐화
객체의 자율성을 보전하기 위해 구현을 외부로부터 감추는 것을 캡슐화라고 합니다. __객체는 상태와 행위를 함께 캡슐화함으로써 충분히 협력적이고 만족스러울 정도로 자율적인 존재가 될 수 있다.__

객체지향의 세계에서 캡슐화는 두 가지 관점에서 사용됩니다.

- 상태와 행위의 캡슐화
- 사적인 비밀의 캡슐화

#### 상태와 행위의 캡슐화
객체는 상태와 행위의 조합입니다. 객체는 스스로 자신의 상태를 관리하며 상태를 변경하고 외부에 응답할 수 있는 행동을 내부에 함께 보관합니다. 객체는 상태와 행동을 하나의 단위로 묶는 자율적인 실체입니다. 이 관점에서 캡슐화를 데이터 캡슐화라고 합니다.

객체는 상태와 행위를 한데 묶은 후 외부에서 반드시 접근해야만 하는 행위만 골라 공용 인터페이스를 통해 노출합니다. 따라서 __데이터 캡슐화는 인터페이스와 구현을 분리하기 위한 전제 조건입니다.__

__객체가 자신의 상태를 스스로 관리 할 수 있어야 하기 때문에 데이터 캡슐화는 자율적인 객체를 만들기 위한 전제 조건이기도 합니다.__

#### 사적인 캡슐화
객체는 외부의 객체가 자신의 내부 상태를 직접 관찰하거나 제어할 수 없도록 막기 위해 의사소통 가능한 특별한 경로만 외부에 노출합니다. ex. setter()

#### 책임의 자율성이 협력의 품질을 결정한다

__책임의 자율성을 강조하는 이유는 객체의 책임이 자율적일수록 협력이 이해하기 쉬워지고 유연하게 변경할 수 있게 되기 때문에 책임이 얼마나 자율적인지가 협력의 설계 품질을 결정하게 되기 때문입니다.__ 항목별로 자세히 알아보겠습니다.

1. __외부관점__ : 자율적인 책임은 협력을 단순하게 만든다.
   - 자율적인 책임은 의도를 명확하게 표현함으로써 협력을 단순하고 이해하기 쉽게 만듭니다. 세부적인 사항들을 무시하고 의도를 드러내는 하나의 문장으로 표현함으로써 단순하게 만듭니다.
2. __내부관점__ : 자율적인 책임은 외부와 내부를 명확하게 분리합니다.
   - 책임이 자율적이기 때문에 약속된 책임만 완수할 수 있으면 어떤 방법을 선택할지는 전적으로 스스로 권한을 가집니다. __요청하는 객체가 몰라도 되는 사적인 부분이 객체 내부로 캡슐화 되기 때문에 인터페이스와 구현이 분리__됩니다.
3. 책임이 자율적일 경우 책임을 수행하는 내부적인 방법을 변경하더라도 외부에 영향을 미치지 않습니다.
   - 책임이 자율적일수록 변경에 의해 수정되어야 하는 범위가 좁아지고 명확해집니다. 변경의 파급효과가 객체 내부로 캡슐화되기 때문에 두 객체 간의 결합도가 낮아집니다.
4. 자율적인 책임은 협력의 대상을 다양하게 선택할 수 있는 유연성을 제공합니다.
   - 책임이 자율적일수록 협력이 좀 더 유연해지고 다양한 문맥에서 재활용될 수 있어 설계가 유연해지고 재사용성이 높아집니다.
5. 객체가 수행하는 책임들이 자율적일수록 객체의 역할을 이해하기 쉬워집니다.
   -  객체가 수행하는 책임들이 자율적일수록 존재 이유를 명확하게 표현할 수 있습니다. 왜냐하면 객체는 동일한 목적을 달성하는 강하게 연관된 책임으로 구성되기 때문입니다. 책임이 자율적일수록 객체의 응집도를 높은 상태로 유지하기 쉬워집니다.
   
정리해보겠습니다.
> 자율적인 책임의 강력함
1. 협력이 이해하기 쉬워지기 때문에 적절한 "추상화"가 가능합니다.
2. 객체의 "외부"와 "내부"의 구분이 명확해져 높은 응집도와 낮은 결합도를 갖게 됩니다.
3. 변경에 의한 파급효과를 제한할 수 있어 캡슐화가 증진됩니다.
4. 인터페이스와 구현이 명확히 분리됩니다.
5. 유연하게 변경할 수 있는 동시에 다양한 문맥에서 재활용할 수 있게 됩니다. 즉, 설계의 "유연성"과 "재사용성"이 향상됩니다.

__객체지향의 강력함을 누리기 위한 출발점은 책임을 자율적으로 만드는 것입니다.
이것은 선택하는 메시지에 따라 달라집니다.__


### 6. 객체 지도

#### 기능 설계 vs 구조 설계
__"유일하게 변하지 않는 것은 모든 것이 변한다는 사실 뿐이다"__

자주 변경되는 기능이 아니라 안정적인 구조를 따라 역할, 책임, 협력을 구성해야 합니다.

미래에 대비하는 가장 좋은 방법은 변경을 예측하는 것이 아니라 변경을 수용할 수 있는 선택의 여지를 설계에 마련해 놓는 것이기 때문입니다.


#### 기능 설계 vs 구조 설계
- 기능(function) 설계: 제품이 사용자를 위해 무엇을 할 수 있는가
- 구조(structure) 설계: 제품의 형태가 어떠해야 하는가
기능과 구조라는 두 가지 측면을 함께 녹여 조화를 이루도록 만들어야 합니다.
즉, 훌륭한 기능을 제공하는 동시에 새로운 기능을 빠르고 안정적으로 추가할 수 있어야 합니다.

#### 두 가지 재료: 기능과 구조
#### 안정적인 재료: 구조
- 사용자나 이해관계자들이 도메인에 관해 생각하는 개념과 개념들 간의 관계로 표현합니다.
#### 도메인 모델
- 도메인(domain): 사용자가 프로그램을 사용하는 대상 분야
- 도메인 모델: 소프트웨어가 목적하는 영역 내의 개념과 개념 간의 관계 등을 주의 깊게 추상화한 형태
최종 제품은 사용자의 관점을 반영해야 합니다. 디자인 모델을 기반으로 만든 시스템이 사용자 모델을 정확하게 반영하도록 노력해야 합니다. 따라서, 소프트웨어 객체는 도메인 모델을 통해 표현되는 도메인 객체들을 은유해야 합니다.

#### 불안정한 재료: 기능
사용자의 목표를 만족시키기 위해 책임을 수행하는 시스템의 행위로 표현합니다.
#### 유스케이스
- 사용자와 시스템 간 이뤄지는 __상호작용의 흐름__을 정리하는 기법
- 사용자들의 목표를 중심으로 연관된 시스템의 기능적 __요구사항__들을 이야기 형식으로 __묶을 수 있습니다.__
- 도메인과 객체는 유스케이스로부터 자동으로 변환되는 것이 아니며, 영감이나 힌트만이 들어 있을 뿐이다.

#### 재료 합치기: 기능과 구조의 통합
#### 책임-주도 설계
- 요구사항들을 식별하고 도메인 모델을 생성한 후, 소프트웨어 클래스에 메소드를 추가하고, 요구사항을 충족시키기 위한 객체들 간 메시지 전송을 정의합니다.
- 사용자의 관점에서 시스템의 기능을 명시하고, 사용자와 설계자가 공유하는 안정적인 구조를 기반으로 기능을 책임으로 변환하는 체계적인 절차를 따라야 합니다.
- 안정적인 도메인 모델을 기반으로 시스템의 기능을 구현해야 합니다.
- 도메인 모델과 코드를 밀접하게 연관시키기 위해 노력해야 합니다.

### 7. 함께 모으기

-  개념, 명세, 구현 세 가지 관점이 클래스에 명확하게 드러나야 합니다.
-  인터페이스와 구현을 분리해야 합니다.


#### 객체지향 설계의 세 가지 관점
1. 개념 관점 (Conceptual Perspective)
   - 사용자가 도메인을 바라보는 관점
   - 설계는 도메인 안에 존재하는 개념과 개념 사이의 관계
2. 명세 관점 (Specification Perspective)
   - 소프트웨어 내 객체들의 인터페이스를 바라보는 관점
   - 객체가 협력을 위해 무엇을 할 수 있는가에 초점
3. 구현 관점 (Implementation Perspective)
   - 객체들이 책임을 수행하는 데 필요한 동작하는 코드를 작성하는 관점
   - 객체의 책임을 어떻게 수행할 것인가에 초점

#### 코드와 세 가지 관점
코드는 세 가지 관점을 모두 제공해야 합니다.
개념 관점: 도메인을 구성하는 중요한 개념과 관계를 클래스에 반영해야 합니다.
명세 관점: 변화에 탄력적인 공용 인터페이스를 만들어야 합니다.
구현 관점: 클래스 내부 속성과 메서드는 철저히 캡슐화되어야 합니다.

#### 도메인 개념을 참조하는 이유
__도메인 개념 안에서 적절한 객체를 선택하는 것은 도메인에 대한 지식을 바탕으로 코드의 구조와 의미를 쉽게 유추할 수 있게 합니다.__
좀 더 쉽게 변화에 대응할 수 있게 됨으로써 시스템 유지보수성을 향상시킵니다.

#### 인터페이스와 구현을 분리하라
명확하게 명세 관점과 구현 관점으로 나누어 볼 수 있어야 합니다.
명세 관점, 즉 인터페이스가 설계를 주도하고 구현을 통해 세부사항을 추상화하면 설계의 품질이 향상됩니다.

### 7.1 커피 전문점 도메인
커피 전문점에서 커피를 주문하는 과정을 객체들의 협력 관계로 바라보겠습니다.

#### 커피 전문점

### 7.1.1 메뉴판 객체
  - 메뉴판에는 커피 메뉴가 적혀 있습니다. (여기서는 아메리카노, 카푸치노, 카라멜 마키아또, 에스프레소 네 가지 종류만 있다고 가정)
- 메뉴 항목들 역시 객체로 볼 수 있습니다.
  - 따라서 메뉴판은 네 개의 메뉴 항목 객체들을 포함하는 객체라고 볼 수 있습니다.
- 손님 객체
  - 손님 역시 하나의 객체입니다. 메뉴판을 보고 바리스타에게 원하는 메뉴 항목을 주문합니다.
- 바리스타 객체
  - 바리스타는 자율적으로 커피를 제조하는 객체로 볼 수 있습니다. 바리스타가 제조하는 커피 역시 자신만의 경계를 가지는 객체로 볼 수 있습니다.
  
객체지향의 관점에서 커피 전문점이라는 도메인은 손님 객체, 메뉴 항목 객체, 메뉴판 객체, 바리스타 객체, 커피 객체로 구성된 작은 세상입니다.

우리는 동적인 객체를 정적인 타입으로 추상화해서 복잡성을 낮춥니다.
상태와 무관하게 동일하게 행동할 수 있는 객체들은 동일한 타입으로 분류할 수 있습니다.

타입 간에 어떤 관계가 존재하는지 살펴보겠습니다.

- 메뉴판 타입 - 메뉴 항목 타입
  - 하나의 메뉴판 객체는 다수의 메뉴 항목 객체로 구성되어 있으며, 메뉴판과 메뉴 항목 객체는 따로 떨어져 존재하지 않으며 하나의 단위로 움직입니다.
  - 메뉴 항목 객체가 메뉴판 객체에 포함돼 있다고 할 수 있는데 이를 __포함 관계__ 또는 __합성 관계__라고 합니다.
- 메뉴판 타입 - 손님 타입
  - 손님 타입은 메뉴판 타입을 알고 있어야 원하는 커피를 선택할 수 있습니다.
  - 한 타입의 인스턴스가 다른 타입의 인스턴스를 포함하지는 않지만 서로 알고 있어야 할 경우 이를 연관 관계라고 합니다.
- 손님 타입 - 바리스타 타입
  - 손님 타입은 바리스타 타입에게 주문을 해야 합니다.
- 바리스타 타입 - 커피 타입
  - 바리스타 타입은 커피를 제조해야 하므로 커피 타입을 알고 있어야 합니다.

이처럼 소프트웨어가 대상으로 하는 영역인 도메인을 단순화해서 표현한 모델을 도메인 모델이라고 합니다. 이제 적절한 객체에게 적절한 책임을 할당해보겠습니다.

### 7.1.2. 설계하고 구현하기
#### 커피를 주문하기 위한 협력 찾기
협력을 설계할 때는 메시지를 먼저 선택하고 그 후에 메시지를 수신하기에 적절한 객체를 선택해야 합니다.

- 메시지를 수신할 객체는 메시지를 처리할 책임을 맡게 되고 객체가 수신하는 메시지는 객체가 외부에 제공하는 공용 인터페이스에 포함됩니다.

> 커피를 주문하라
- 손님 객체가 커피를 주문할 책임을 맡게 됩니다.
- 따라서 메시지를 처리할 객체는 손님 타입의 인스턴스입니다.

>메뉴 항목을 찾아라
- 손님은 메뉴 항목에 대해서는 알지 못하기 때문에, 메뉴 항목을 누군가가 제공해 줄 것을 요청합니다.
- 메시지를 수신한 객체는 메뉴 이름에 대응되는 메뉴 항목을 반환해야 합니다.
메뉴판 객체는 메뉴 항목 객체를 포함하기 때문에 이 책임을 처리할 수 있는 가장 적절한 후보입니다.

>커피를 제조하라
- 손님은 메뉴 항목에 맞는 커피를 제조해달라고 요청할 수 있습니다.
- 손님은 커피를 제조하는 메시지의 인자로 메뉴 항목을 전달하고 반환값으로 제조된 커피를 받아야 합니다.
- 바리스타는 커피를 제조하는 데 필요한 모든 정보를 알고 있으므로 바리스타 객체가 커피를 제조할 책임을 맡게 됩니다.

협력에 필요한 객체의 종류와 책임, 주고받아야 하는 메시지에 대한 대략적인 윤곽이 잡혔습니다.
이제 메시지를 정제함으로써 각 객체의 인터페이스를 구현 가능할 정도로 상세하게 정제해보겠습니다.

#### 인터페이스 정리하기
손님 인터페이스
- '커피를 주문하라'라는 오퍼레이션이 포함돼야 합니다.
메뉴판 인터페이스
- '메뉴 항목을 찾아라'라는 오퍼레이션을 제공해야 합니다.
바리스타 인터페이스
- '커피를 제조하라'라는 오퍼레이션을 제공합니다.
커피 인터페이스
- '생성하라'라는 오퍼레이션을 제공합니다.

객체들을 포괄하는 타입을 정의한 후 식별된 오퍼레이션을 타입의 인터페이스에 추가해야 합니다.

협력을 통해 식별된 타입의 오퍼레이션은 외부에서 접근 가능한 공용 인터페이스의 일부입니다.
따라서 인터페이스에 포함된 오퍼레이션 역시 외부에서 접근 가능하도록 공용(public)으로 선언되어있어야 합니다.

```
class Customer {
    public void order(String menuName) {}
}

class MenuItem {
}

class Menu {
    public MenuItem choose(String name) {}
}

class Barista {
    public Coffee makeCoffee(MenuItem menuItem) {}
}

class Coffee {
    public Coffee(MenuItem menuItem) {}
}
```

#### 구현하기
__Customer__
- Customer는 Menu에게 menuName에 해당하는 MenuItem을 찾아달라고 요청해야 합니다.
- MenuItem을 받아 이를 Barista에게 전달해서 원하는 커피를 제조하도록 요청해야 합니다.
- 객체 참조를 얻는 다양한 방법이 있지만 여기서는 Customer의 order() 메서드의 인자로 Menu와 Barista 객체를 전달받는 방법을 선택합니다.
```
public class Customer {
    public void order(String menuName, Menu menu, Barista barista){
        MenuItem menuItem = menu.choose(menuName);
        Coffee coffee = barista.makeCoffee(menuItem);
    }
}

```
구현 도중에 객체의 인터페이스가 변경될 수 있습니다.
- 설계 작업은 구현을 위한 스케치를 작성하는 단계일 뿐, 구현 그 자체일 수는 없습니다.

__Menu__
Menu는 menuName에 해당하는 MenuItem을 찾아야 하는 책임이 있습니다.다.
이 책임을 수행하기 위해서는 Menu가 내부적으로 MenuItem을 관리하고 있어야 합니다.
간단하게 Menu가 MenuItem의 목록을 포함하게 하겠습니다.
```
public class Menu {
    private List<MenuItem> items;

    public Menu(List<MenuItem> items){
        this.items = items;
    }
    public MenuItem choose(String name){
        for(MenuItem each : items){
            if(each.getName().equals(name)){
                return each;
            }
        }
        return null;
    }
}
```
MenuItem의 목록을 Menu의 속성으로 포함시킨 결정 역시 클래스를 구현하는 도중에 내려졌습니다.

- 객체의 속성은 구현에 속하기 때문에 "캡슐화"되어야 합니다.
- 가장 훌륭한 방법은 인터페이스를 정하는 단계에서는 객체가 어떤 속성을 가지는지, 또 그 속성이 어떤 자료 구조로 구현됐는지를 고려하지 않는 것입니다.

__Barista__
Barista는 MenuItem을 이용해서 커피를 제조합니다.
```
class Barista {
    public Coffee makeCoffee(MenuItem menuItem) {
        Coffee coffee = new Coffee(menuItem);
        return coffee;
    }
}
```
__Coffee__
Coffee는 자기 자신을 생성하기 위한 생성자를 제공합니다.
커피 이름과 가격을 속성으로 가지고 생성자 안에서 MenuItem에 요청을 보내 커피 이름과 가격을 얻은 후 Coffee의 속성에 저장합니다.
```
class Coffee {
    private String name;
    private int price;
    
    public Coffee(MenuItem menuItem) {
        this.name = menuItem.getName();
        this.price = menuItem.cost();
    }
}
```
__MenuItem__
MenuItem은 getName()과 cost() 메시지에 응답할 수 있도록 메서드를 구현해야 합니다.
```
public class MenuItem {

    private String name;
    private int price;

    public MenuItem(String name, int price) {
        this.name = name;
        this.price = price;
    }

    public int cost(){
        return price;
    }

    public String getName(){
        return name;
    }
}
```
MenuItem의 인터페이스를 구상하는 오퍼레이션들을 MenuItem을 구현하는 단계에 와서야 식별했습니다.

인터페이스를 통해 실제로 상호작용을 해보지 않은 채 인터페이스의 모습을 정확하게 예측하는 것은 불가능에 가깝습니다.
설계를 간단히 끝내고 최대한 빨리 구현해 돌입해야 합니다.

### 7.1.3 코드의 세 가지 관점

#### 코드는 세 가지 관점을 모두 제공해야 한다.
> __개념 관점__
- 개념 관점에서 코드를 바라보면 Customer, Menu, MenuItem, Barista, Coffee 클래스가 보입니다.
- 소프트웨어 클래스가 도메인 개념의 특성을 최대한 수용하면 변경을 관리하기 쉽고 유지보수성을 향상시킬 수 있습니다.

>__명세 관점__
- 명세 관점은 클래스의 인터페이스를 바라봅니다.
- 인터페이스를 수정하면 해당 객체와 협력하는 모든 객체에게 영향을 미칠 수밖에 없습니다.
- 최대한 변화에 안정적인 인터페이스를 만들기 위해서는 인터페이스를 통해 구현과 관련된 세부 사항이 드러나지 않게 해야 합니다.

>__구현 관점__
- 구현 관점은 클래스의 내부 구현을 바라봅니다.
- 클래스의 메서드와 속성은 구현에 속하며 공용 인터페이스의 일부가 아닙니다. 따라서 메서드와 속성은 철저하게 클래스 내부로 캡슐화되어야 합니다.
- 훌륭한 객체지향 프로그래머는 하나의 클래스 안에 세 가지 관점을 모두 포함하면서도 각 관점에 대응되는 요소를 명확하고 깔끔하게 드러낼 수 있습니다.

세 가지 관점이 명확하게 드러날 수 있도록 하는 것이 변경에 유연하게 대응할 수 있는 객체지향 코드를 작성하는 가장 빠른 길입니다.

#### 도메인 개념을 참조하는 이유
어떤 메시지가 있을 때 그 메시지를 수신할 객체를 선택하기 위한 첫 번째 전략은 도메인 개념 중에서 가장 적절한 것을 선택하는 것입니다.

도메인 개념 안에서 적절한 객체를 선택하는 것은 도메인에 대한 지식을 기반으로 코드의 구조와 의미를 쉽게 유추할 수 있게 합니다.
소프트웨어 클래스가 도메인 개념을 따르면 변화에 쉽게 대응할 수 있습니다.

#### 인터페이스와 구현을 분리하라
"__"인터페이스와 구현을 분리하라."__

명세 관점과 구현 관점이 뒤섞여 함부로 어지럽히지 못하게 해야 합니다.

- 명세 관점은 클래스의 안정적인 측면을 드러내야합니다.
- 구현 관점은 클래스의 불안정한 측면을 드러내야합니다.
- 인터페이스가 구현 세부 사항을 노출하기 시작하면 아주 작은 변동에도 전체 협력이 요동치는 취약한 설계를 얻을 수밖에 없습니다.
- 클래스를 봤을 때 클래스를 명세 관점과 구현 관점으로 나눠볼 수 있어야 합니다.

캡슐화를 위반해서 구현을 인터페이스 밖으로 노출해서도 안 되고, 인터페이스와 구현을 명확하게 분리하지 않고 흐릿하게 섞어놓아서도 안 됩니다.

세 가지 관점 모두에서 클래스를 바라볼 수 있으려면 훌륭한 설계가 뒷받침되어야 합니다.
