## EC2(Elastic Computer Cloud)
- 컴퓨터 리소스에 대해 전반적 관리를 해주며 , 가동중인 EC2 가상 서버를 EC2인스턴스라고 하는, 개별 인스턴스에 대해 총체적인 권한을 받는다.
- 컴퓨터를 빌려 원격으로 접속해 사용하는 서비스로, 워크로드에 맞게 컴퓨팅, 메모리, 스토리지, 네트워킹을 최적화할 수 있습니다

# 인스턴트 유형
## 람다
- 이벤트를 총해 입력 인자가 발생하면 연산 과정으로 출력 인자를 바꾸는 이벤트 기반의 컴퓨팅 서비스
- EC2와 다르게 오직 소스코드만 사용하여 인프라에 대한 관리가 필요하지 않는 완전 관리형 컴퓨팅 서비스

## EC2
- 도커 컨테이너 서비스. 도커란 서버 가상화 기술 중 하나

## 라이트세일
- 완전 관리형 가상 서버 서비스
- 가상 서버를 구축할 수 있는 가장 손쉬운 서비스 , 별도로 소스코드 업로드나 설정 없이 클릭으로도 서버를 구축할 수 있다.

## 빈스톡
- EC2의 설정을 매우 쉽게 돕는 서비스
- 서버의 런타임부터 운영체제 환경까지 관리해주면 개발자는 소스코드만 업로드하여 바로 운영가능

# 스토리지 
## S3
-안정성과 보안이 완벽한 스토리지를 손쉽게 만들 수 있게 해주녀 서비스 운영 시 생성되는 이미지.동영상,오디오 파일들을 저장할 수 있게함

## 스토리지 게이트웨이(Storage Gateway)
- 기존 온프로미스 환경과 AWS를 연결해주는 게이트웨이 서비스
- AWS를 통해 파일로 연결되기 때문에 더 높은 보안성과 신뢰성을 기대
- 기존 데이터들을 클라우드 환경으로 옮기지 않고도 바로 적용이  

## EBS(Elastix Block Storage)
- EC2와 연결할 수 있는 저장장치 서비스 
- EC2의 하드디스크,SSD 스냅샷을 통해 언제든 EC2를 백업할 수 있으며, 문제가 생겼을때 복원도 가능하다.

# 데이터베이스 
## RDS
- 관계형 데이터베이스(RDBMS)를 구축하는 서비스
- 6개의 RDBMS 데이터베이스 엔진을 선택 가능
- 높은 가용성 자랑, 자동으로 백업과 복원 등을 지원

## 다이나모 DB
- No-SQL 기반의 완전 관리현 데이터베이스
- 백업이나 복원, 스케일링과 같은 관리 작업을 자동으로 수행
- 저렴한 비용
- 네트워크의 로그 데이터나 게임, IoT처럼 대량의 데이터 발생 시 저장하기 적합
- 

## 엘라스틱 캐시
- RDS와 다이나모 DB가 SSD 영역에서 입출력이 되는 반해, 엘라스틱(Elasticache)는 메모리에 데이터를 저장하여 더욱 빠르게 입출력이 가능

## Red Shift
- 완전 관리형 SWL 데이터 웨어 하우스
- 대용량의 정형 데이터를 처리하는 데 사용
- 페타바이트 규모의 데이터 퀴리를 저렴한 가격에 유지 보수 및 운영할 수 있도록 만듦

# 네트워크

## VPC
- 가상 네트워크망(VPN, Virtual Private Network) 구축 지원 서비스
- 서비스 보안 수준을 결정하거나 EC2나 RDS와 같은 AWS 서비스들을 적합한 권한이 있는 사용자들만 접속할 수 있게 한다

## Route53
- DNS(Domain Name System) 서비스
- 도메인을 AWS 리소스와 연결 할때 사용 
- DNS 서비스는 주소창에 컴퓨터 IP 주소를 입력할 필요가 없어 도메인 주소로 접속할 수 있도록 해주는 서비스

