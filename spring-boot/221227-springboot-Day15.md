## 오늘 공부한 것

- spring boot
    - jpa
        - repository 인터페이스, 클래스 분석
        - hibernate vs jpa


    - 실습
        - 에러 처리 구현
        - 뷰 연결


- 알고리즘
    - 여행경로 dfs로 풀기



## 느낀점

repository, crudRepo, PagingAndSortingRepo, JPARepo를 살펴보며 jpa repository에 대한 이해를 할 수 있었다. 스프링 데이터 jpa에서 entityManager를 사용해서 하는 일들, 트랜잭션 관리하는일을 한번 감싸서 구현해놓았기 때문에 직접적으로 entityManager, rollback등을 사용할 일이 없다는 것을 알 수 있었다. 우리는 잘 포장된 것을 사용하되, 정말 필요할때나 이해가 되지 않을 때 포장을 들여다 보면 된다. 
        
