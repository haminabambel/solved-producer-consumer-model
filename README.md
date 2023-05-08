Download Link: https://assignmentchef.com/product/solved-producer-consumer-model
<br>
<span class="kksr-muted">Rate this product</span>

In the C programming language create a pair of programs following the producer / consumer model to pass messages between each other using a message queue.



The consumer program will be responsible for:

– setting up the queue with the following key:

– ftok(“.”, ‘Z’)

– displaying characters that are sent by the producer where the message type is 100

– removing the queue and exiting once a lowercase q or uppercase Q is received

The producer will:

– access the queue created by the consumer

– prompt the user to input one keyboard character at a time followed by the enter key

– send the keyboard character to the consumer process via message queue