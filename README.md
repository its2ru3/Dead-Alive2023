## Dead & Alive 2023
**Implementing SPEEDY block cipher on Quantum Computers and breaking it using Grover's algorithm.**

Thus proving that the encryption strength increases linearly on increasing number of rounds(iterations of encryption) in Quantum case which was increasing exponentially in Classical case.

### SPEEDY Block Cipher
It's an encryption algorithm designed in 2021 for fast encryption of memory, cache, CPU instructions etc. Specially designed for big hardware infrastructures. Other previously available encryption algorithms like PRINCEv2 are only good for IoT devices.

Research paper [link](https://inspirehep.net/files/e1ea5c9944ae30efb760b9618fb66d6d)

Presentation [link](https://docs.google.com/presentation/d/1X7FdU8G2H8d7kmMFAKEzxPAb9kTiJNjvbksLn_9aSm8/edit?usp=sharing)

## Run yourself
At this point of time, because of need of large number of qubits which are not available on cloud, this program is not capable of giving outputs when run on actual hardware. But IBM provides simulator_stabilizer (Simulator type - Clifford simulator) which can run this code.

<div class="custom-alert" style="border: 1px solid #372c12; background-color: #372c12; padding: 10px;">
  <strong>Warning:</strong> Requires huge amount of RAM in your system.
</div>
<br>


In my case, I ran it on Google Colab where I had only 12GB of RAM which crashes because of huge amount of data transfer.

## To-do
> Configure the code such that the data coming from IBM simulator's server is stored in Disk instead of RAM.

> Write some more code to evaluate more cost parameters. 
