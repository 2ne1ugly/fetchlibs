# fetchlibs

1. SW 홈페이지
2. 라이선스
3. docker repo
4. 용도 
5. 버전 / sha256

## busybox
1. https://www.busybox.net/
2. https://www.busybox.net/license.html / GPLv2
3. https://hub.docker.com/_/busybox
<<<<<<< Updated upstream
4. 경량 linux 유틸리티 커맨드 라이브러리로, 자주 사용되는 리눅스 명령어들을 제공하는 바이너리로써 도커(고성능 경량 VM) 이미지 제작에 사용합니다.
5. 1.36.1
=======
4. 경량 linux 유틸리티 커맨드 라이브러리, 자주 사용되는 리눅스 명령어들을 제공하는 바이너리로써 도커(고성능 경량 VM) 이미지 제작에 사용합니다.
5. 1.36.1 / 743663a45073c802af5675803ac8ca4eaa97dc187c8ff75ca9f68f868fc43bcd
>>>>>>> Stashed changes

## kafka
1. https://kafka.apache.org/
2. https://github.com/apache/kafka/blob/trunk/LICENSE / Apache 2.0
3. https://hub.docker.com/r/bitnami/kafka
<<<<<<< Updated upstream
4. 분산형 이벤트 스트리밍 플랫폼으로, 지연 처리 및 대기열 시스템을 통한 서버 반응성과 영속성을 위해서 사용합니다.
5. - 2.8.1 
   - 3.5.2
   - 3.7.1
=======
4. 분산형 이벤트 스트리밍 플랫폼, 지연 처리 및 대기열 시스템을 통한 서버 반응성과 영속성을 위해서 사용합니다.
5. - 2.8.1 / b8ce16574dac4b2d2f670f11d8076b3337250c6f4ed5cc38e999c24481187ae2
   - 3.5.2 / 62bb18f05eccc54b75805731f88d9f13bbfd8f7d0ca3c46f564d7650b9c18d3c
   - 3.7.1 / 6344a6a1ad95a7ff439ac52fc55886adc353c4a292608d549f232cec87c0e4c4  

>>>>>>> Stashed changes

## kafka-ui
1. https://docs.kafka-ui.provectus.io/
2. https://github.com/provectus/kafka-ui/blob/master/LICENSE / Apache 2.0
3. https://hub.docker.com/r/provectuslabs/kafka-ui
4. kafka 모니터링 서버(대시보드), kafka의 성능 및 부하 지표를 보여줍니다.
5. - 0.7.2 / 3317027d297e7589e1a522d0d0340b344c8c6dc1dcbb7d54af64118576416f6a

## rabbitMQ
1. https://www.rabbitmq.com/
2. - 둘 중 선택
   - https://github.com/rabbitmq/rabbitmq-website/blob/main/LICENSE-Apache-2.0 / Apache 2.0
   - https://github.com/rabbitmq/rabbitmq-website/blob/main/LICENSE-MPL-2.0 / MPL 2.0
3. https://hub.docker.com/_/rabbitmq
4. kafka의 대안으로, 성능은 조금 떨어지나 반응성이 더 높고 더 많은 라이브러리들과 호환이 됩니다.
5. - 3.13.6-management  / 7061488f5b6c9b79033f1fed601f932b68f1d1f530d7309cf0c8491e6b89c146
   - 3.13.6 / 14d4a77db9547bab3aab6a3977320875b8e508759ddf1cc1130e9e5398c1f19e

## prometheus
1. https://prometheus.io/
2. https://github.com/prometheus/prometheus/blob/main/LICENSE / Apache 2.0
3. https://hub.docker.com/r/prom/prometheus
4. 시스템 부하 모니터링 툴로, 서버 장애 원인을 앞서서 발견하여 예방하고 발생시 원인 파악에 도움이 됩니다.
5. - 2.53.1 / 7eca3ac4486925cd0d7703eca5a62ac2b118aaff5606fe27181702ab0f1a97c8

## traefik
1. https://traefik.io/ 
2. https://github.com/traefik/traefik/blob/master/LICENSE.md / MIT
3. https://hub.docker.com/_/traefik
4. 요청 분산과 중계(프록시)를 맡는 서버 입니다. 서버간 부하를 분산시키고 점진적 서버 버전 변경(카나리) 무중단 업데이트를 가능하게 만듭니다.
5. - 3.1.1 / 31038d78d4e12fbdd5fd5c9eff53dc6568b83002de677edd17c3b0bf7feb396e

## zookeeper
1. https://zookeeper.apache.org/
2. https://github.com/apache/zookeeper/blob/master/LICENSE.txt / Apache 2.0
3. https://hub.docker.com/_/zookeeper
4. Kafka를 올리기위한 클러스터 관리 서버 입니다. Kafka를 실행시키는데 필요합니다. 
5. - 3.6 / acb560db1b9447c0035ed3c9776538b096aa39c50b3cc87749077fcc059602b0  
   - 3.7 / 85685f47fade0f81760ca8a34adce77418b56bef56e2aafee143d2f64582b67a
   - 3.9.2 / 773f674cc6929e9e058ad8e01f213d842256b4ac0a59fd9426d7d808dcc374c6


/------------------------------/


