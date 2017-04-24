# model

1) Users (email . password)

	-Postings
	-Comments

2) Postings (title . body . user_id)
	belongs -User
	-Comments

3) Comments (content . user_id . posting_id)
	belongs to postings and user

===============================

#Controller

Controllers for each model

User => device gemfile (gemfile is premade file (import))

================================

#View (CSS / Bootstrap)