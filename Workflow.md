### Example Workflow

#### Purchase Horses:
Farm manager registers a new horse:  
`"Added 'Thunder' (Breed: Arabian, Age: 3) for $5,000 on 2023-10-01."`

---

#### Assign to Training:
Trainer assigns Thunder to a training program:  
`"Thunder assigned to Trainer John on 2023-10-05."`

---

#### Mark Ready for Auction:
Farm manager marks Thunder as ready for auction:  
`"Thunder ready for auction on 2023-12-01 with an expected price of $10,000."`

---

#### Register for Auction:
Auction manager registers Thunder for an auction:  
`"Thunder registered for Auction #123 on 2023-12-15."`

---

#### Record Sale:
Auction manager records Thunder's sale:  
`"Thunder sold for $12,000 to Buyer Jane on 2023-12-15."`

---

#### View Reports:
Farm owner views auction performance and inventory status:

**Rules for Maintaining Inventory**:
1. The total number of horses in the field (including those in training, newcomers, and auction) must always be **10**.
2. If horses sold exceed horses in the field, calculate how many new horses to buy:
3. Ensure that after purchasing new horses, the total number of horses in the field is restored to **10**.

---

### Example Scenario

#### Current Inventory:
- Horses in Training: 3  
- Horses Ready for Auction: 2  
- Horses Sold: 5
  - Horses to Buy = Horses Sold - (Horses in Training + Horses Ready for Auction + Newcomers)
- Newcomers: 0  

#### Calculation:

Since the total number of horses in the field is already **10** (3 in training + 2 ready for auction + 5 newcomers), no new horses need to be purchased.

---

#### Updated Inventory After Purchase:
- Total Revenue: $50,000
- Horses Sold: 5
- Horses in Training: 3
- Horses Ready for Auction: 2
- Horses in Field (Total): 10  
- Newcomers: 0  
- Horses to Buy: 0  
