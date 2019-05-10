1. What is the purpose of using _sessions_?
   `using sessions allows us to store information about a client so that it can be used multiple times regardless of the times the system re-renders this way we don't have to keep putting credentials every time`

1. What does bcrypt do to help us store passwords in a secure manner.
   `by including hashing, adding up hashing rounds and adding extra implementation to encrypt the password, bcrypt makes it so that a hacker will have a very long time, essentially impossible time hacking the password`

1. What does bcrypt do to slow down attackers?
   `it makes it so the hacker needs to use a hash, know the used algorithm and how many rounds were used to generate the hash initially`

1. What are the three parts of the JSON Web Token?
   `the three parts are the header, the payload and the signature`
