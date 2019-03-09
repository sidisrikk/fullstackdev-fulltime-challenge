# Locker Design

1. Online reservation
    - reserve unit page + Sub unit status (available/reserved)
    - e-payment page
    - gql mutation for reservation
2. Back-end server
    - Pub unit status+passcode (available/reserved)
    - payments confirm -> produce status + passcode
3. locker node
    - Sub unit status+passcode (available/reserved)
    - reserve unit page + Sub unit status + passcode (available/reserved)
    - coin payment & change
    - passcode to unlock unit page
