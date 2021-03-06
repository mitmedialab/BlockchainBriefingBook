# Summary

The wide distribution of many copies of the entire ledger, coupled with the use of cryptographic signing trees, ensure a very long term and publicly verifiable record of all transactions conducted on the Bitcoin and Ethereum public blockchains.  The "public" nature and large communities of these two blockchain are significant factors underlying their potential as part of a general use, long term and global electronic archive resource.

The specific mechanism that makes public blockchain technology potentially suitable as part of a legal notice and records or data management service is called OP_RETURN.  OP_RETURN provides a small amount of space for arbitrary data associated with a transaction conducted on the blockchain.  The key point is that OP_RETURN can be used to embed [any data at all](https://21.co/learn/embedding-data-blockchain-op-return/#embedding-data-in-the-blockchain-with-op_return) into a blockchain. 

## Discussion

I think of this as equivalent to the "memo" or "note" line on the bottom left of a  personal check. Depending on the style of writing and the size of the paper check, this line can legibly contain perhaps 20-50 characters (a sentence or two at most) but is intended for just a few words to record a note about the context or purpose of the payment. It may not matter to a bank or transaction processor whether or note a party includes many or few characters in a memo field on a paper check, provided the practice does not destroy the material or obscure other information on the check. However, adding additional data to a transaction on the Bitcoin or Ethereum can have more serious implications for the speed and performance of the entire blockchain as a system.

According to [Bitcoin Core release 0.9.0](https://bitcoin.org/en/release/v0.9.0#opreturn-and-data-in-the-block-chain)

> This change is not an endorsement of storing data in the blockchain. The OP_RETURN change creates a provably-prunable output, to avoid data storage schemes – some of which were already deployed – that were storing arbitrary data such as images as forever-unspendable TX outputs, bloating bitcoin's UTXO database.
> Storing arbitrary data in the blockchain is still a bad idea; it is less costly and far more efficient to store non-currency data elsewhere.

According to the [Bitcoin Wiki](https://en.bitcoin.it/wiki/OP_RETURN) applications of OP_RETURN include "digital asset proof-of-ownership, and (it) has at times been used to convey additional information needed to send transactions."   

> Is storing data in the blockchain acceptable?
Many members of the Bitcoin community believe that use of OP_RETURN is irresponsible in part because Bitcoin was intended to provide a record for financial transactions, not a record for arbitrary data. Additionally, it is trivially obvious that the demand for external, massively-replicated data store is essentially infinite. Despite this, OP_RETURN has the advantage of not creating bogus UTXO entries, compared to some other ways of storing data in the blockchain.

The practice of using a public blockchain primarily to address an electronic records related business or legal requirement is at the essence of many products, services and even entire business models.  For example, see:
* [Factom](https://www.factom.com): "...redundant record keeping problems, proof of compliance, and data integrity." 
* Chainpoint: "...open standard for creating a timestamp proof of any data, file, or process.
Anchor an unlimited amount of data to multiple blockchains. Verify the integrity and existence of data without relying on a trusted third-party."
* [Tierion Hash API](https://tierion.com/docs/hashapi): "Tierion’s Hash API lets you anchor data to the blockchain while keeping your data private. This API operates independently from the main Tierion application and the Data API. Use of the Hash API is free up to 100 records per second and 1,000 records per hour."

## "Long Term" and "Permanent" Duration

To consider whether blockchain technology can enable a permanent records on must understand the meaning of permancence in context.  The logical and scientific challenges raised by the general concept of a "permanent record" are considerable (perhaps unsurmountable). General consensus or widely accepted standards from law, policy and practice are also lacking a crisp definition, scope or criteria.

According to the [Dr. Micah Altman](http://informatics.mit.edu), the MIT Libraries Director of Research and Head Scientist, from an archival perspective, one can say that a long-term institutional committment is usually needed to provide credible assurance of "long term" records preservation (he chose not comment on the concept of a "permanent" committment).  Informally, one can guess perhaps a 50 year committment would be a credible approximation of what might be intended in general practice as a "permanent" record preservation.

Relevant Links:

* [The Truth About Blockchain](https://hbr.org/2017/01/the-truth-about-blockchain): By Marco Iansiti and Karim R. Lakhani, published in the Harvard Business Review, JANUARY–FEBRUARY 2017 ISSUE: "Explore the Archive ... Contracts, transactions, and the records of them are among the defining structures in our economic, legal, and political systems. ... record transactions between two parties efficiently and in a verifiable and permanent way."

* [Using Blockchain to Keep Public Data Public](https://hbr.org/2017/03/using-blockchain-to-keep-public-data-public): By Brian Forde,  published at the Harvard Business Review site on March 31, 2017.

* [Blockchain: your permanent record of business](https://www.ibm.com/blogs/southeast-europe/blockchain-permanent-record-business) Posted by Peter_Gersak, CTO, IBM South East Europe on April 25, 2017

* [Blockchain for Recordkeeping](https://www.w3.org/2016/04/blockchain-workshop/slides/Lemieux-Blockchain_for_Recordkeeping.pdf) Presentation by Victoria L. Lemieux to the W3C Workshop, MIT June 29, 2016 Boston, MA 






