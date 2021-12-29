<<<<<<< HEAD
# decentralized-voting-app
=======

Follow the instructions to deploy on remix

1) Enter 2 strings for Ballot Name and Proposal Eg: "Ballot", "Prime Minister" and hit deploy (that current address would be Ballot Address)

2) click startVote then copy the address of any voter from code and replace the Account address. (Currently the ballotOfficialAddress is restricted to vote)
3) enter Candidate Id (1,2,3,4) and hit voteCandidate
4) check if the voteCount is reflected in candidate by entering same candidateId in candidates field.
5) check if it's reflected in totalVotes
6) copy the voter address and enter in the registerVoter field and check the voted field (should be true)
7) 1 voter can vote can only 1 candidate
8) change the address to vote from a different voter
9) hit endVote
10) click Winner and the winning candidate name would display
