# Influencer-Sponsor-Coordination-Platform-V2
Influencer-Sponsor Coordination system V2 (Using JS and Python API)

It is a platform where a Sponsor can run a camapign and request influencer for an ad request for the campaign and upon completion of the ad, sponsor can pay the influencer. 

1. Registration page for Sponsor and Influencers
2. Single Login page for Admin/Sponsor/Influencer
3. Daily reminder email is automatically sent to influencer if any influencer has not respond to an ad request.
4. Monthly report of the activities of a sponsor is also sent via email on monthly basis.
5. Admin can monitor the platform and flag inappropriate user/campaigns/ad-request.
6. There is a page which shows statistics of the uses.

Technologies used:
1. Flask RESTful API
2. Flask Security
3. VUE JS for frontend
4. Celery for schedule tasks
5. Redis for cache
6. Python for application logic
