![image](https://github.com/user-attachments/assets/3cf60ace-83e8-46b9-a1c0-94ff9267b208)


If you are looking for a circuit which can be used to latch the output in response to an input signal, then this circuit can be used for the intended purpose very effectively and also very cheaply.

A momentary input trigger is applied to the base of T1,which switches it for a fraction of a second depending upon the length of the applied signal.

The conduction of T1 immediately switches T2 and the connected relay.

However at the very instant a feedback voltage also appears at the base of T1 via R3 from the collector of T2.

This feed back voltage instantly latches the circuit and keeps the relay activated even after the trigger from the input is removed.

Parts List

    R1, R3 = 100k,
    R2, R4 = 10K,
    C1 = 1uF/25V
    D1 = 1N4148,
    T1 = BC547,
    T2 = BC557
    Relay = 12V, SPDT
