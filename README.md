# 드론을 활용한 주문/배송
기능요건
- 고객이 주문을 하면, 주문 정보를 바탕으로 드론 배송이 시작된다
- 고객이 주문 취소를 하게 되면, 주문 정보는 삭제되나 취소 정보는 별도 저장한다
- 주문과 배송 서비스는 게이트웨이를 통해 고객과 통신한다
 
비기능 요건
- 주문 취소는 반드시 배송취소가 전제가 되어야 한다.

추가 기능요건
- 고객은 주문서비스에서 배송 상태를 열람할 수 있어야 한다.


---------------------------
Event Storming

![event_storming](https://user-images.githubusercontent.com/68858009/106541068-94966d80-6544-11eb-9ba7-5077b4fd39d9.png)

---------------------------
DDD 적용

![ddd1](https://user-images.githubusercontent.com/68858009/106553608-0b3f6500-655d-11eb-915a-80ca868a852d.png)

---------------------------
폴리글랏

![persistance](https://user-images.githubusercontent.com/68858009/106555764-902c7d80-6561-11eb-87e9-d80a66a4686f.png)
