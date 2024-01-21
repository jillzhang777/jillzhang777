# Welcome to YY ECOMM Professional Recruitment

## About Us

```python
class TeamLeader:
    def __init__(self, name, team_size):
        self.name = name
        self.team_size = team_size

class RecruitmentAgency:
    def __init__(self, name, locations):
        self.name = name
        self.locations = locations

# Team Information
kiki = TeamLeader(name="Kiki", team_size=10)
web3_fintech_internet_team = [kiki, "consultants", "senior consultants"]

# Agency Information
yy_ecomm = RecruitmentAgency(name="YY ECOMM", locations=["Hong Kong", "Shenzhen, China"])

# Introduction
print(f"Currently {kiki.name} is leading a team of {kiki.team_size} {', '.join(web3_fintech_internet_team)}.")
print(f"Our team is focused on placing Web3/FinTech/Internet mid-to-senior level positions.")
print("Feel free to ping me up if you have any hiring or expanding needs across Asia Pacific.")

print(f"\n{yy_ecomm.name} is one fast-growing professional recruitment consultancy, specializing in the placement of candidates")
print("in permanent, contract, temporary, and interim positions with clients around the world.")
print(f"The Group has operations in {', '.join(yy_ecomm.locations)}.")

# Company Overview
print("\n## An Established Brand\n")
print("The company has established a leading presence in Internet/Fintech/Web3 for professional recruitment around the world")
print("and has positioned itself in certain other markets, which offer the opportunity for future growth.")
