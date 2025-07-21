In real-time image transmission applications such as IoT, surveillance, and medical imaging, secure and efficient encryption is crucial. However, conventional encryption methods like AES can be computationally expensive, requiring high FPGA resources and power.
To solve this, we propose a hybrid encryption model combining:

Compressive Sensing (CS) → Reduces image size before encryption, improving speed and efficiency.
Chaotic Encryption → Uses hyperchaotic sequences for strong security.

(1)Preprocessing: Convert the image into a numerical matrix.

(2)Key Generation: Use a chaotic system to generate pseudo-random encryption keys.

(3)Pixel Scrambling: Rearrange pixel positions based on the chaotic sequence.

(4)Diffusion: Modify pixel values using chaotic operations (XOR, addition, etc.).

(5)Decryption: Reverse the process using the same chaotic key.

FPGA-Based Implementation → Achieves real-time performance and low power consumption.
