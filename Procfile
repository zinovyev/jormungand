web:         bundle exec passenger start -p $PORT --max-pool-size $PASSENGER_MAX_POOL_SIZE 3
worker:      QUEUES=default,paperclip,mailers bundle exec rake jobs:work
