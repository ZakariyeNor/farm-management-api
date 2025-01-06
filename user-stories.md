### User Stories

#### 1. Horse Purchase
**Register a Horse**: As a Farm Manager, I can register newly purchased horses so that I can keep track of all horses in the system.  
> **AC1** Given a form with fields (Horse ID, Name, Breed, Age, Purchase Date, Purchase Price), the farm manager can submit the form.  
> **AC2** Then the horse is added to the system.  

**View Purchased Horses**: As a Farm Manager, I can view a list of all purchased horses so that I can monitor the current inventory.  
> **AC1** Given a list of horses, the farm manager can view their details (Horse ID, Name, Breed, Age, Purchase Date, Purchase Price).  

---

#### 2. Training Program
**Assign Horse to Training**: As a Trainer, I can assign horses to a training program so that I can track their progress.  
> **AC1** Given a form with fields (Horse ID, Training Start Date, Trainer Name, Training Status), the trainer can submit the form.  
> **AC2** Then the horse is added to the training program.  

**Update Training Status**: As a Trainer, I can update the training status of a horse so that I can reflect their progress in the system.  
> **AC1** Given a horse in the training program, the trainer can update its status (e.g., In Progress, Completed).  

**View Horses in Training**: As a Farm Manager, I can view a list of horses in the training program so that I can monitor their progress.  
> **AC1** Given a list of horses in training, the farm manager can view their details (Horse ID, Training Start Date, Trainer Name, Training Status).  

---

#### 3. Auction Preparation
**Mark Horse as Ready for Auction**: As a Farm Manager, I can mark horses as ready for auction so that I can prepare them for sale.  
> **AC1** Given a horse, the farm manager can mark it as ready for auction with fields (Horse ID, Auction Ready Date, Expected Auction Price).  

**View Horses Ready for Auction**: As a Farm Manager, I can view a list of horses ready for auction so that I can plan the auction event.  
> **AC1** Given a list of horses marked for auction, the farm manager can view their details (Horse ID, Auction Ready Date, Expected Auction Price).  

---

#### 4. Auction Registration
**Register Horse for Auction**: As an Auction Manager, I can register horses for an auction event so that I can track which horses are being sold.  
> **AC1** Given a form with fields (Auction ID, Horse ID, Auction Date, Reserve Price), the auction manager can submit the form.  
> **AC2** Then the horse is registered for the auction.  

**View Registered Horses**: As an Auction Manager, I can view a list of horses registered for an auction so that I can manage the event.  
> **AC1** Given a list of registered horses, the auction manager can view their details (Auction ID, Horse ID, Auction Date, Reserve Price).  

---

#### 5. Auction Sales
**Record Horse Sale**: As an Auction Manager, I can record the sale of a horse so that I can track revenue.  
> **AC1** Given a form with fields (Horse ID, Sale Price, Buyer Name, Sale Date), the auction manager can submit the form.  
> **AC2** Then the sale is recorded in the system.  

**View Sold Horses**: As an Auction Manager, I can view a list of sold horses so that I can analyze sales performance.  
> **AC1** Given a list of sold horses, the auction manager can view their details (Horse ID, Sale Price, Buyer Name, Sale Date).  

---

#### 6. Financial Tracking
**View Auction Revenue**: As a Farm Owner, I can view the total revenue from auctions so that I can assess profitability.  
> **AC1** Given a report, the farm owner can view fields (Total Revenue, Total Horses Sold, Average Sale Price).  

**View Purchase Costs**: As a Farm Owner, I can view the total cost of purchased horses so that I can calculate ROI.  
> **AC1** Given a report, the farm owner can view fields (Total Purchase Cost, Number of Horses Purchased).  

---

#### 7. Inventory Management
**View Horses in Training**: As a Farm Manager, I can view a list of horses still in training so that I can plan future auctions.  
> **AC1** Given a list of horses in training, the farm manager can view their details (Horse ID, Training Start Date, Trainer Name, Training Status).  

**View Unsold Horses**: As a Farm Manager, I can view a list of unsold horses so that I can decide whether to re-auction or keep them.  
> **AC1** Given a list of unsold horses, the farm manager can view their details (Horse ID, Auction Ready Date, Expected Auction Price).  

---

#### 8. Data-Driven Decision Making
**View Auction Performance Report**: As a Farm Owner, I can view a report of auction performance so that I can decide how many horses to buy next.  
> **AC1** Given a report, the farm owner can view fields (Number of Horses Sold, Total Revenue, Average Sale Price, Horses Still in Training).  

**Compare Purchase Costs vs. Auction Revenue**: As a Farm Owner, I can view a comparison of purchase costs vs. auction revenue so that I can make informed decisions.  
> **AC1** Given a report, the farm owner can view fields (Total Purchase Cost, Total Revenue, ROI).  
