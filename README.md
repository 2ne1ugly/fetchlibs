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
4. 경량 linux 유틸리티 커맨드 라이브러리로, 자주 사용되는 리눅스 명령어들을 제공하는 바이너리로써 도커(고성능 경량 VM) 이미지 제작에 사용합니다.
5. 1.36.1

## kafka
1. https://kafka.apache.org/
2. https://github.com/apache/kafka/blob/trunk/LICENSE / Apache 2.0
3. https://hub.docker.com/r/bitnami/kafka
4. 분산형 이벤트 스트리밍 플랫폼으로, 지연 처리 및 대기열 시스템을 통한 서버 반응성과 영속성을 위해서 사용합니다.
5. - 2.8.1 
   - 3.5.2
   - 3.7.1

## kafka-ui
1. https://docs.kafka-ui.provectus.io/
2. https://github.com/provectus/kafka-ui/blob/master/LICENSE / Apache 2.0
3. https://hub.docker.com/r/provectuslabs/kafka-ui
4. kafka 모니터링 서버(대시보드), kafka의 성능 및 부하 지표를 보여줍니다.
5. - 0.7.2

## rabbitMQ
1. https://www.rabbitmq.com/
2. - 둘 중 선택
   - https://github.com/rabbitmq/rabbitmq-website/blob/main/LICENSE-Apache-2.0 / Apache 2.0
   - https://github.com/rabbitmq/rabbitmq-website/blob/main/LICENSE-MPL-2.0 / MPL 2.0
3. https://hub.docker.com/_/rabbitmq
4. kafka의 대안으로, 성능은 조금 떨어지나 반응성이 더 높고 더 많은 라이브러리들과 호환이 됩니다.
5. - 3.13.6-management    (대시보드로 모니터링 가능한 버전)
   - 3.13.6

## prometheus
1. https://prometheus.io/
2. https://github.com/prometheus/prometheus/blob/main/LICENSE / Apache 2.0
3. https://hub.docker.com/r/prom/prometheus
4. 시스템 부하 모니터링 툴로, 서버 장애 원인을 앞서서 발견하여 예방하고 발생시 원인 파악에 도움이 됩니다.
5. - 2.53.1

## traefik
1. https://traefik.io/ 
2. https://github.com/traefik/traefik/blob/master/LICENSE.md / MIT
3. https://hub.docker.com/_/traefik
4. 요청 분산과 중계(프록시)를 맡는 서버 입니다. 서버간 부하를 분산시키고 점진적 서버 버전 변경(카나리) 무중단 업데이트를 가능하게 만듭니다.
5. - 3.1.1

## zookeeper
1. https://zookeeper.apache.org/
2. https://github.com/apache/zookeeper/blob/master/LICENSE.txt / Apache 2.0
3. https://hub.docker.com/_/zookeeper
4. Kafka를 올리기위한 클러스터 관리 서버 입니다. Kafka를 실행시키는데 필요합니다. 
5. - 3.6
   - 3.7
   - 3.9.2

/------------------------------/


