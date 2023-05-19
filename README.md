The contract is intialized with the addresses of the buyer, seller, zuluagent and the price of the item.
The buyer can deposit the required amount of Ether using the deposit() function.
The buyer and seller can each approve the release of the funds using the approvebybuyer() and approvebyseller() functions, respectively. Once both parties have approved, the funds are released to the seller. 
If there is a dispute, the zuluagent can resolve it using the dispute() function. If the zuluagent sides with the buyer, the funds are refunded to the buyer. If the zuluagent sides with the seller, the funds are released to the seller.
If there is an excess amount of Ether in the contract, it is refunded to the buyer using  the releasepayment() function.
The contract assumes that the seller will deliver the goods or services to the buyer before the buyer approves the release funds.
