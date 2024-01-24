# 쿠버네티스 EKS 배포 예제

- docker-compose 로 로컬에서 컨테이너 실행가능
- `./kubernates`에 `Deployment`와 `Service` 를 선언형으로 작성


## EKS 배포 준비

1. EKS 셋업(로드 밸런서, 파드 개수 등 설정)
2. 로컬 환경의 `Kubecontrol`을 `AWS EKS`와 연결하기 (`AWS CLI`를 통해서 손쉽게 가능)
3. `kubectl apply -f 파일명` 을 통해 파드 배포