
카프카에서 메시지가 저장되는 기본 단위로 default 1GB로 설정한다
Retention 정책에 따라 몇일동안 얼마만큼의 용량을 유지할지 설정하고 log segment가 꽉 차면 새로운 로그 세그먼트가 만들어지며넛 오래된 로그 데이터는 삭제되기 시작한다

디스크가 꽉 차면 더 이상 로그가 쌓이지 않거나 삭제가 발생할 수 있다.
