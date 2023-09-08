Commands to run Task2:

1) To execute secure_chat to communciate with Bob from client side
./secure_chat -c bob1

2) To execute secure_chat with Alice
./secure_chat -s 

Commands to run Task3:

1) Poison the host file:
bash ~/poison-dns-alice1-bob1.sh

2) To execute secure_chat_interceptor to communciate with bob from client side
./secure_chat_interceptor -c bob1

3) To execute secure_chat_interceptor for alice1
./secure_chat_interceptor -s 

Commands to run Task4:

1) Poison the host file:
bash ~/poison-dns-alice1-bob1.sh

2) To execute task4 to communciate with bob from client side 
./task4 -c bob1

3) To execute task4 from server side
./secure_chat -s

4) To execute task4 from trudy side 
./try -m alice1 bob1