## 𝐁𝐥𝐨𝐜𝐤 𝐂𝐡𝐚𝐢𝐧 𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐲

> - Unit I : Mathematical Foundation for Blockchain
> - Unit II: Feature Engineering

## 𝐔𝐧𝐢𝐭 𝐈  : 𝐌𝐚𝐭𝐡𝐞𝐦𝐚𝐭𝐢𝐜𝐚𝐥 𝐅𝐨𝐮𝐧𝐝𝐚𝐭𝐢𝐨𝐧 𝐟𝐨𝐫 𝐁𝐥𝐨𝐜𝐤𝐜𝐡𝐚𝐢𝐧

<div align=center>
  <br>

  ![image](https://user-images.githubusercontent.com/68887544/193409617-f3fbb402-316e-47a2-9301-af2b1098ccc5.png)

  <br>
</div>

- Cryptography:
> - The field of study that deals with the study of secure communication techniques which allows only the sender and intended recipient of a message to view its contents.

- Symmetric Cryptography:
> - Kind of Cryptography where encryption key is same as the decryption key.
> - Also known as secret key Cryptography or shared key Cryptography or private key cryptography.
> - Key needs to be established before any communication begins.
> - Types:
>   - Stream Cipher
>     - Applies the encryption algorithms one bit at a time.
>   - Block cyphers
>     - Applies the encryption algorithm block by block after dividing the plain text into blocks of a predefined size.
>     - Example: DES and AES i.e. Data Encryption Standard & Advanced Encryption Standard.

- Asymmetric Cryptography:
> - Kind of cryptography where encryption key is distinct from the decryption key.
> - Another name is public key cryptography.
> - It uses both public as well as private keys.
> - Example: RSA, DSA, and ElGammal.
> - They are slower as compared to symmetric key algorithm in terms of computation and hence isn't used for large sized data.

- Elliptic Curve Cryptography (ECC):
> - Collection of points that satisfies a specific mathematical equation is known as Elliptic curve cryptography.
> - Elliptic curve equation look something like this:
>   - `y^2 = x^3 + ax + b`
> -

`^Will study tomorrow, I think! My brain isn't working`

- Cryptographic hash functions:
> - A one way function which generates a fixed length output string for any kind of variable length input string is called as cryptographic hash function.
> - We can't compute input using the output and hence it is a one way function.
> - Properties:
>   - Pre-image resistance.
>   - Weak collision resistance.
>   - Collision resistance.

- Digital Signature Algorithm (DSA):
> - DSA stands for Digital Signature Algorithm.
> - Digital signature algorithm is used for digital signature and its verification.
> - It is based on the mathematical principle of modular exponentiation and discrete logarithm.
> - It involves 4 steps:
>   - Key generation
>   - Key distribution
>   - Signing
>   - Signature verification
>
> - Steps at signer's end:
>   - Message or hash is hashed using a hashing function to a create a digest.
>   - Sender uses the private key to sign the generated digest in step 1 using the signature algorithm.
>
> - Steps at receivers end:
>   - Recipient on receiving the data and signature runs a verifier algorithm and used sender's public key.
>   - If the generated hash value from above step matches the hash value sent by the sender, then the recipient is satisfied with the data and the signature. Else if matching fails the signature of the sender is not valid.
> - The digital signature process can be divided into 2 steps:
>   - Signature generation
>   - Signature verification


- Merkel Tree:
> - Merkel tree is a binary tree in which each node contains hash pointers.
> - Merkel tree is used to verify the authenticity of the data being sent or received.
> - Merkel tree is also known as binary hash tree.
> - In merkel tree, each node other than leaf nodes are hash of every children node of the given node.
> - It employs hash function to preserve the integrety of the data.
> - An input of data is broken up into blocks labeled D1 to D4. Each of these blocks are then hashed using a hash function.
> - Then each pair of nodes are recursively hashed until we reach the root node, which is a hash of all nodes below it.
> - The root node of the merkel tree is known as merkel root.
> - When data is shared among parties, then data is shared using regular channel and merkel root is shared using secure channel.
> - Intermediate hash values can be shared from regular or secure channels as per requirements.
> - As data stars coming in, the verifier verifies the data by hashing each node and comparing it with the hash values received for that segment.
> - After the entire document is received, the merkel root computed will be compared with the merkel root received from the secure channel. If data is manipulated in the process, then value of hash and in turn merkel root would change and this will help the verifier verify the authenticity of the data.


## 𝐔𝐧𝐢𝐭 𝐈𝐈 : 𝐅𝐞𝐚𝐭𝐮𝐫𝐞 𝐄𝐧𝐠𝐢𝐧𝐞𝐞𝐫𝐢𝐧𝐠

<div align=center>
  <br>

![image](https://user-images.githubusercontent.com/68887544/193409634-5e012177-6bae-4fd5-93ce-c7555473f8e9.png)

  <br>
</div>

- Centralized Systems:
> - Centralized systems are the systems that works on client-server system architecture in which a central authority has every rights and is incharge of the system.
> - For example, you are messaging someone on facebook. Facebook is the one that verifies the message is valid, and then delivers the message to the user.

- Advantage of Centralized system:
> - Reduced cost
> - Quick decision implementation.
> - Command chain.

- Limitation of Centralized system:
> - Security
> - Trust
> - Privacy
> - Single point of failure
> - Scalable limitation
> - Inflexibility
> - Access and diversity

- Decentralized System:
> - They are the systems where each node is master of it's own, i.e. there doesn't exist any master node for nodes in the system.
> - Blockchain Technology made decentralization possible.

- Advantages of Decentralization:
> - Provides a trustless environment.
> - improves data reconciliation
> - Reduces points of weakness
> - Optimizes resource distribution.

- Layers of blockchain:
> - Application Layer : The user can code desired functionality and build the application.
> - Execution Layer : It operates the execution of all the instructions that were defined in application layer.
> - Semantic Layer: This layer is used for the validation of blocks created in the network and also validating the transactions performed in the blockchain.
> - Propagation Layer: It handles the peer-to-peer communications between the network nodes.
> - Consensus layer: The main aim of this layer is to make sure that all the nodes must agree on a common state of the shared ledger, the layer also works on the security and safety of the blockchain.


- Why blockchain is important?
> - Blockchain and it's use is important because of following properties and functionality that it provides:
>   - Security: Blockchain being trustless protocol and it having decentralized nature makes blockchain very secure.
>   - Transparency: Every change, every detail and everything is very transparent as everything is visible to all the participants in consideration.
>   - Time of transaction is less.
>   - It increases efficiency in finance.
>   - Scope of Innovation: there exists a massive scope for innovation in BT.
>   - No middleman in the transactions
>   - Blockchain has numerous application in various technological fields.
>   - Ease of traceability.


- Blockchain Adoption So Far:
> - Following industries have started adopting blockchain technology.
>   - Automotive
>   - Banking and Financial services
>   - Government
>   - Healthcare and life sciences
>   - Supply chain
>   - Insurance
>   - Media and entertainment
>   - Retail and consumer good
>   - Telecommunication
>   - Travel and transport
>   - etc.

---
