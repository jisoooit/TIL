## 오늘 공부한 내용

- 배포
    - 쉘 스크립트를 통한 배포 실습
        - ec2에 deploy.sh 를 만들어 그것만 실행함으로써 배포가 되게 함
        - 그러나 새로운 push가 있
을 때마다 ec2에 접속하여 deploy.sh 파일을 실행시켜줘야해서 번거로움

    - github action & aws S3 & codeDeploy 를 통한 배포 실습
        - ec2 인스턴스 생성
        - s3버킷 생성
        - codedeploy 생성
        - 역할 부여
        - iam 사용자 생성
        - appspec.yml 작성
        - deploy.sh 작성
        - github action 스크립트 작성

- 데이터 베이스
    - 인덱스
    - group by 와 having
    - join
        - inner join
        - outer join



## 느낀점

어제 배포 방법에 대해 공부했었는데 오늘 실습 해보았다. 처음에는 너무 복잡해보였는데 천천히 찾아보며 결국 성공했다. deploy.sh 작성하는 부분에서 폴더 명이랑 경로 때문에 시간이 많이 소요됐지만, 처음이라 그렇지 이제 확실히 알았으니 다음에 할때는 문제 없을 것 같다. 그리고 iam user만들때 엑세스 키 방식이 이제 기본값이 아닌 것 같다. 나는 엑세스키가 익숙해서 그걸로 접속했지만, 다른 방법을 찾아봐야겠다.

