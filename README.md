# 🍕 Fast Pizza React 앱이란?

> [!NOTE]
> Fast Pizza React 앱은 React로 구축된 현대적인 다중 페이지 피자 주문 웹 애플리케이션입니다. 이 앱은 사용자가 피자 옵션을 탐색하고, 항목을 장바구니에 추가하고, 계정을 만들지 않고도 주문할 수 있는 편리한 플랫폼을 제공합니다. 이 앱은 간단하고 직관적이며 피자를 사랑하는 사람들에게 쉽고 빠르게 사용할 수 있도록 설계되었습니다.

### 프로젝트 요구사항:
- [x] 사용자가 메뉴에서 하나 이상의 피자를 주문할 수 있는 매우 간단한 애플리케이션 🍕
- [x] 사용자 계정과 로그인이 필요하지 않으며, 사용자는 애플리케이션을 사용하기 전에 이름을 입력만 하면 됩니다 ✍️
- [x] 피자 메뉴는 변경될 수 있으므로 API에서 로드되어야 합니다 🌐
- [x] 사용자는 주문하기 전에 장바구니에 여러 피자를 추가할 수 있어야 합니다 🛒
- [x] 주문에는 사용자의 이름, 전화번호 및 주소만 필요합니다 📝
- [x] 가능하다면, GPS 위치를 제공하여 배달을 더 쉽게 할 수 있습니다 📍
- [x] 사용자는 장바구니 가격에 20%를 추가하여 "우선 주문"을 할 수 있습니다 ⚡
- [x] 주문은 API로 주문 데이터를 (사용자 데이터+선택한 피자) 포함한 POST 요청을 보내는 방식으로 이루어집니다 💌
- [x] 결제는 배달 시 이루어지므로 애플리케이션에서 결제 처리 기능은 필요 없습니다 💳❌
- [x] 각 주문은 고유한 ID를 부여받으며, 사용자가 나중에 주문 ID로 주문을 확인할 수 있습니다 🔢
- [x] 사용자는 주문을 한 후에도 "우선 주문"으로 표시할 수 있어야 합니다 ✅

### Features and Pages

| Featured Categories | Necessary pages   | URL Params      |
| ------------------- | ----------------- | --------------- |
| User                | HomePage          | /               |
| Menu                | Pizza menu        | /menu           |
| Cart                | Cart              | /cart           |
| Order               | Placing new order | /order/new      |
| Order               | Looking up order  | /order/:orderId |

### Technologies & Tools:

<p>
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/reactrouter/reactrouter-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tailwindcss/tailwindcss-original.svg" title="npm" alt="npm" width="40" height="40"/>&nbsp;
</p>

## Fast Pizza 앱의 주요 기능들:
### 🛒 피자 메뉴
- 피자 메뉴는 동적으로 변경할 수 있으며 API를 통해 쉽게 업데이트할 수 있어, 사용자가 최신 메뉴를 항상 확인할 수 있습니다.
### 👤 사용자 계정 및 로그인 불필요
- 사용자는 주문을 하기 위해 계정을 만들 필요가 없습니다. 앱을 사용하기 전에 이름만 입력하면 됩니다.
###  🍽️ 다수의 피자 주문 가능
- 사용자는 하나 이상의 피자를 장바구니에 추가하여 주문을 할 수 있으며, 이를 통해 주문을 유연하게 조정할 수 있습니다.
### 📍 위치 서비스
- 배달을 더 쉽게 하기 위해 사용자는 GPS 위치를 제공할 수 있습니다. 이를 통해 정확한 배달이 가능합니다.
### 💳 우선순위 주문
- 사용자는 추가 요금 20%를 지불하고 주문을 "우선순위"로 지정할 수 있어, 빠른 배달을 보장합니다.
### 📦 고유 주문 ID
- 모든 주문은 고유한 ID를 부여받아, 사용자가 나중에 주문을 추적하거나 조회할 수 있도록 합니다.
### 📱 주문 양식
- 주문을 하기 위해 사용자는 이름, 전화번호, 주소만 입력하면 됩니다. 앱 내에서는 결제 처리가 필요하지 않으며, 결제는 배달 시 이루어집니다.
### 🛑 주문 후 우선순위 변경 가능
- 주문이 완료된 후에도 사용자는 자신의 주문을 "우선순위"로 업데이트할 수 있어, 주문 관리에 유연성을 제공합니다.
