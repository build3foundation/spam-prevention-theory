# Construction Administration Spam Prevention Theory
A WIP paper with the hypothesis that strict measures and calculus to keep change-reqeust spam under control ultimately lead to a better result, a safer building, and a stronger business relationship.

Ultimately what is being proposed and considered in thei work in progress paper is a decision making framework that can automate the calculus regarding the risk of saying "yes" every time someone asks for help.

Note from how weight is calculated on Substrate, which prevents DDoS (ie spam) attacks:

Why benchmark a pallet
Denial-of-service (DoS) is a common attack vector for distributed systems, including blockchain networks. A simple example of such an attack would be for a user to repeatedly execute an extrinsic that involve intensive computation. To prevent users from spamming the network, we charge fee to the user for making that call. The cost of the call should reflect the computation and storage cost incurred to the system such that the more complex the call, the higher the fee. However, we still want to encourage users to use our blockchain system, so we also want this estimated cost to be relatively accurate so we don't charge users more than necessary.


