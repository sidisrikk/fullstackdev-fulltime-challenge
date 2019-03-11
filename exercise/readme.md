# Locker Design

1. [Online reservation](https://github.com/sidisrikk/locker-web-reservation) ** not implement yet
    - reserve unit page + Sub unit status (available/reserved)
    - e-payment page
    - gql mutation for reservation
2. [Back-end server](https://github.com/sidisrikk/locker-backend) 
    - Pub unit status+passcode (available/reserved)
    - payments confirm -> produce status + passcode
3. [locker node](https://github.com/sidisrikk/locker-node) - box machine
    - Sub unit status+passcode (available/reserved)
    - reserve unit page + Sub unit status + passcode (available/reserved)
    - coin payment & change
    - passcode to unlock unit page
