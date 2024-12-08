Imagine a banknote which is left on a table in a cafe. Anyone passing by can take it. Ownership in the physical world then means protecting banknotes and other physical objects from being taken or approached even by unintended parties. 

Digital banknotes are different. They can protect themselves with the help of public-key cryptography. That is, a banknote may be associated with public key of its owner. And then only owner (or owners) of a secret key corresponding to the public key is able to spend it. There is need to be tech-savvy or have discipline to store secret keys, on the other hand, it would still be easier, for many at least, to maintain digital secret than physically protecting notes or coins, especially when relocating them from one place (or one jurisdiction) to another.

Also, digital world allows for more, in particular, we can have protection by two public keys instead of just one. For example, a father can create a banknote which is protected by both father's and son's public keys, to authorize son's payments (e.g. when son is trying to spend the digital banknote in a shop, father may check the spending remotely and cosign it, or deny to do so). Even from this simple example it is clearly seen that issue of ownership in the age of digital money could be more complex than in physical world, as here we have collective ownership instead of individual. 

But digital banknotes allowing for even more. In the first place, it is possible to have even more complex signatures. For example, modern cryptography allows for threshold signatures with up to thousands of participants, which is allowing, for example, for a banknote to be controlled by (majority vote of) small town. In the second place, it is possible to mix cryptographic statements with machine-executable logic, making money ownership **programmable**. And with tokenization of real-world assets(RWA), we, similarly, have programmable property rights for RWAs too.

Blockchain is ideal execution environment, as its state at given moment of time (block) is fully deterministic. However, we can imagine other options, e.g. a note can refer to trusted non-blockchain environment its script will be executed against, or, in case of Central Bank Digital Currency (CBDC), deterministic trusted environment could be provided by a central bank.

And then, with public and private programmable money of different kind, we have a question what does it mean to *own* money in this new digital world, i.e. what constitutes *ownership*.

There could be different approaches here, considering complexity of the topic, for starters, the following taxonomy could be used:

* if at the current moment or after tolerable period of time (such as one month, or one year even) script is always associated with a public key PK regardless all other variables of execution enviroment, we can talk about individual ownership here with an owner associated with the public key PK. This definition can be relaxed: if it is known that multiple keys related to the same person, we can use multiple keys instead of just one in our definition. 

This definition of individual ownership may seem natural to holders of cryptocurrencies, such as Ergo, using Ergo wallets, as they usually see their ERGs and other tokens associated with an address (starting with *9*, for example, *9fLVZF4eKoAKi155L9nDNGKomgCgjDm2ZXyPMdpGbwy7erNjhJp*), which is encoding a public key. However, individual ownership can be associated with more complex scripts, such as "PK && true", or e.g. timelock for one hour after which a banknote may be spend by a public key owner.

* if at the current moment or after tolerable period of time script is always associated with multiple public keys which are possibly related to different people, we define it as cooperative ownership

* if ownership may vary with time or depending on other conditions (state of other banknotes, blockchain hashrate etc), or can't be associated with any public key, we define it as contractual ownership

And with tokenized real world assets, tokenized rights to make decisions or even update contracts on the blockchain, we have individual/cooperative/contractual property rights for different assets. And our framework can be useful for legally defining property rights. 

Another use case is doing money issuance and payments while considering possible violations of ownership rights, for example:

* it could be prohibited for state-related actors to issue CBDC banknotes to make social or other payments to individuals with any other form or ownership but individual (some central banks already playing with limited-use CBDC notes for social payments)

* it could be allowed or prohibited for private entities to issue cooperative or contractual notes for individuals, or there could be certain limits on contract templates allowed 

We are just in the beginning of defining what could be allowed for programmable notes issued by public or private sector, and this framework hopefully would be a good starting point.




