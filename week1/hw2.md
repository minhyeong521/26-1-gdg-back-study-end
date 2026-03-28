상품기능 API 명세서 
기능        Method      URL

상품기능
상품등록     Post   /products
상품목록조회  Get   /products
개별 상품 정보 상세 조회 Get    /products/{productId}
상품 정보 수정 Put  /products/{productsId}
상품 삭제   Delete  /products/{productsId}

주문기능
주문정보생성    Post    /orders
주문목록조회    Get     /orders
개별 주문 정보 상세 조회    Get     /orders/{ordersId}
주문 취소       Delete      /orders{ordersId}