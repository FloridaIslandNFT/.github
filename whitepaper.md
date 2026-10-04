# Florida Island white paper

## 1. The project at a glance

This project uses digital shares for an island. The island is **1.25 acres**. It is in Marathon, Florida. The island is East Sister Rock Island. The share contract follows the **ERC-1155** token rules. A token is a digital unit on a chain.

Each share you get has a fixed **0.020% base island interest**. This is a right to benefits set in the trust terms. It does not give the holder direct legal title.

- **1,000 received shares** have a total base interest of **20%**.
- **4,000 received shares** have a total base interest of **80%**.
- Five random rent boost shares receive extra rent income.
- Each received rent boost share gets **1% of gross rent from the whole island**.
- All five receive a separate **5% gross rent pool**.
- The rent boost does not add island ownership.

The owner must confirm the first live share cap. The contract allows a cap from **1,000 to 4,000** shares. The cap does not change one share's rights.

Base rent rights use net income. The extra rent boost uses gross income. Net means after costs. Gross means before costs. These amounts do not make a fixed 25% island stake.

### Version 2 and current limits

This version fixes earlier 25% base ownership and base rent claims. Public sales stay off until the chosen contract setup is ready. The cap must be ready too. An auditor must also check the random draw tool.

The test network is **Robinhood Chain Testnet**. This paper does not give a contract address for a live sale. The review setup uses 1,000 shares. The owner must still confirm the first live cap.

Current trust papers must set the rights under law. This contract review does not check title or insurance. It does not check filings or future results. Claims about island condition, history and legal setup need current records. The island team must supply those records.

### Words used in this paper

- **Share:** A small part of the rights set in the trust terms.
- **Wallet:** An app that holds your account. It lets you sign chain requests.
- **ETH:** The coin used to pay on this chain. You also need ETH for fees.
- **Gas:** The fee to send a chain request.
- **Smart contract:** Code on the chain that follows set rules. It tracks shares and funded claims.
- **Blockchain:** A shared record of chain requests. You can read its public records.
- **Testnet:** A chain used to test the app. Test coins do not make this a live island sale.
- **Pending shares:** Shares you paid for but did not get yet.
- **Received shares:** Shares that the contract delivered to an approved wallet. They are no longer just a paid reservation.
- **Base interest:** Your fixed right to trust benefits for each received share. It does not give direct legal title.
- **Net rent:** Rent from the whole island left after costs.
- **Gross rent:** Rent from the whole island before costs.
- **Trust:** The legal body that holds title and sets holder rights.
- **Snapshot:** The saved share count used for a vote.
- **Quorum:** The number of votes needed for a valid result.

## 2. Why the project exists

### 2.1 Background

Buying a whole costly island often needs a lot of money. Digital shares split its rights to money into small parts. The project aims to let more people buy those rights. Contracts based on Ethereum record shares and trades. People can check those records.

### 2.2 Project goals

1. Let people buy small rights to island benefits.
2. Give holders a share of rent and event income.
3. Let holders share gains from a future rise in value or sale.
4. Provide a market where holders can sell shares.

These are project goals. A market or future profit is not promised.

## 3. The island and shares

### 3.1 Property details

- **Location:** Marathon, Florida, USA.
- **Land:** A 1.25-acre island, plus rights to extra seabottom land.
- **Old planning value:** The first plan used **$15,000,000**. This is not a checked current appraisal.
- **Old rent estimate:** The first plan used about **$100,000 a month**, with special events included. This is not a checked report of income now or a promised return.

Read current owner reports in the reporting contract. Check the date and records that support each report.

### 3.2 Share structure

Each share you get has a fixed base island interest. It is **0.020%**. At 1,000 received shares, the total is 20%. At 4,000, the total is 80%. Rent boosts do not add island equity.

The owner chooses the cap when the contract starts. The cap can be 1,000 through 4,000. The owner must confirm the first cap. Paying to reserve a share does not mean you received it.

The first plan used **$4,500 USD per share**. The deployed sale price uses **ETH**. The owner may change that price. The contract does not accept stablecoins for share purchases.

The owner can set a USD price with an ETH/USD price feed. The feed must be checked and fresh. The feed converts that price to ETH once. The price does not then track the USD price at all times.

## 4. Share rights and random boosts

### 4.1 Base share rights

Each received share gives these rights:

1. **Base island interest:** 0.020%, subject to the trust terms. This includes its base share of future net sale funds.
2. **Base rent income:** 0.020% of whole-island **net rent**.
3. **Votes:** Holders can vote on improvements and key choices under the voting rules. More received shares give more voting weight.

A received rent boost share also gets 1% of whole-island **gross rent**.

At 1,000 received shares, total base rent rights are **20% of net rent**. All five received rent boost shares receive another **5% of gross rent**. These use different income amounts. They do not make 25% ownership or always equal 25% of one income amount.

Rights from shares that are not issued do not go to other holders.

### 4.2 Random boosts

The random draw assigns a limited number of extra benefits. A share may have more than one boost.

#### 1. Stay boost: one share

If the holder meets the rules, they get one free weekend stay each year. The stay is **two nights**.

The draw assigns one stay share across the chosen cap. The full count is promised only after it assigns all shares.

#### 2. Rent boost: five shares

The five rent boost shares share an extra **5% of gross rent**. This rent comes from the whole island. Each received rent boost share gets **1%**. Each keeps the same 0.020% base property and net-rent rights as any share.

The draw assigns five rent boost shares. It draws them across the chosen cap. Only received boost shares earn funded income. A missing share does not increase another share's benefit.

#### 3. Event boost: five shares

An event boost gives **15% off** special island events. These may include weddings or work events. They may include team or family gatherings. Each holder may invite up to **40 guests**.

The draw assigns five event shares. It draws them across the chosen cap. The holder may request a discount for each distinct live event the owner posts. There is no yearly event-count limit. The same checked ID group cannot use one event discount twice.

## 5. Rent and payments

### 5.1 Rent income

Rent income can change. The island team must support reports with records. The old $100,000 monthly estimate was part of a plan.

Rent income is intended to:

1. Pay costs such as repairs, staff and utilities.
2. Pay base dividends of **0.020% of net rent from the whole island** per received share.
3. Fund the separate rent boost of **1% of gross rent from the whole island** per received boost share.

Base rights total 20% at 1,000 received shares, or 80% at 4,000. All five rent boost shares receive 5% gross in total. The extra rent adds income, not equity.

### 5.2 Dividend payments

A dividend is funded income that a holder can claim. The plan calls for payments each quarter. A quarter lasts three months. This aims to reduce network fees and ease record keeping.

A report from the owner does not send rent to the contract. The owner enters whole-island net and gross rent separately. The owner funds these pools with ETH:

- **Base pool = net income × received shares ÷ 5,000.**
- **Boost pool = gross income × received rent boost shares ÷ 100.**

The contract checks the counts of shares received and exact ETH payment. Each pool is split across its own received share count. Rights that are not issued are not funded or shared with other holders.

The owner must supply the ETH. A transfer does not move income that an account already earned. Holders use the app's claim action to withdraw their earned dividends.

## 6. The contract and app

### 6.1 The ERC-1155 standard

ERC-1155 lets one contract support many token types. It supports whole-share amounts as well as shares with special benefits.

Every received share has the same base rights. Share type IDs **0–7** record the boost flags:

- **1:** Stay boost.
- **2:** Rent boost.
- **4:** Event boost.

A type can combine flags. Paid purchases wait for a random draw that can be checked. Shares are assigned in order. The buyer then claims the shares.

### 6.2 Owner tools

The owner dashboard lets the contract owner:

- Enter monthly revenue reports.
- Use each year's appraisal. Enter the island value.
- Fund income payments each quarter.
- Read past wallet actions and trades. Read the royalty fees.

The owner manages the island. Contract records do not prove that a real service or payment took place outside the chain.

### 6.3 Holder tools

Holders use a Web3 wallet that the app supports. MetaMask and a supported Phantom setup are examples. A Web3 wallet signs requests to the chain.

Holders can use the app to:

- Read their share of the island value the owner reports.
- Read rent reports. See funded income you can claim.
- Claim earned income.
- Check their member level and boosts.
- Request a stay with a stay boost.
- Request an event discount with an event boost.

## 7. Member levels

### 7.1 Yearly member perks

The received share count in one wallet sets its level. Each member perk allows **one use per year**.

| Level | Shares held | Yearly benefit |
| --- | --- | --- |
| Level 1 | 1–25 | 10% off one seven-night week |
| Level 2 | 26–50 | 20% off one seven-night week |
| Level 3 | 51–100 | 40% off one seven-night week |
| Level 4 | 101+ | One free seven-night week |

For example, a wallet with 53 received shares gets Level 3. It gets 40% off one week each year.

### 7.2 Tracking use and identity

The contract checks one wallet's level and boosts when a request starts. It checks them again when the owner confirms. The benefit registry tracks the requests. It saves pending requests that are cancelled and requests the owner confirms.

The service start date sets the year. The contract uses the **UTC calendar year**. This runs from January 1 to December 31. UTC is the time standard for this rule.

Each checked ID group gets one seven-night member use per year. The rare two-night stay also has one allowance for the whole collection each year.

The owner links each approved wallet to an ID code with no personal details. The code stands for one checked person. The code is public on the chain. The link stays fixed. Linked wallets and wallets used for recovery share yearly use. New links cannot reset use. Do not add names or ID files to this public code.

A confirmed use consumes the yearly right. Only cancelling a pending request frees its reserved use.

When the owner confirms, the island team accepts the booking. This does not prove a real stay or payment. It does not prove who the holder is under law. The island team must provide dates, open space and the real service.

## 8. A future sale and island value

### 8.1 Selling the island

If the island sells, each received share gets its base interest in net sale funds. That interest is **0.020%**, subject to the trust terms. Net sale funds are the money left after costs that apply.

- 1,000 received shares have a total base share of **20%**.
- 4,000 received shares have a total base share of **80%**.
- A sale bonus for rent boost shares needs an express choice by the owner or trust.
- The **5% rent boost does not also apply to a sale**.
- Extra sale-bonus funding starts off.

The owner can fund the documented base sale right in the app:

**Base sale pool = reported net sale funds × received shares ÷ 5,000.**

The island team reports the net sale funds. The extra pool stays zero while the sale bonus is unconfirmed. The payment checks the base share count. It also checks the rent boost share count.

The owner pays the exact ETH amount. The wallet needs extra ETH for gas. Gas is the network fee. Whole-number sums round down to wei, the smallest ETH unit.

The payment creates funded claims for accounts. It does not transfer a deed or prove the sale. It does not settle the trust agreement's legal duties.

### 8.2 Island value reports

The owner can enter a value from an appraisal each year. The chain stores the report. Holders can use it to track reported changes in value.

## 9. Trading and royalties

### 9.1 Selling or sending shares

Approved wallets can use this market or allowed transfers between wallets. The market saves fee terms when listings or offers start. These include affiliate, royalty and marketing fees. A paid trade uses those saved terms when it settles.

An affiliate fee pays the person who referred a trade. A royalty is a fee owed under the saved trade terms.

ERC-2981 lists royalty fees for outside markets. The contract cannot force an outside market to pay. A plain transfer between wallets does not charge royalty fees.

### 9.2 Transaction records

The app is intended to show share transactions and past prices. Holders and possible buyers can use these records to review past trades. Past prices do not promise future prices.

## 10. Voting and management

### 10.1 Who manages the island

At first, the group that founded the project manages:

- Rent and marketing.
- Repairs and improvements.
- Yearly appraisals and reports on the chain.

### 10.2 Holder votes

The voting contract saves plans for a vote, called proposals. It also saves share snapshots, quorum and results. A snapshot records shares that wallets received at a set point. Quorum is the vote count needed for a valid result.

Votes last from **one to thirty days**. Approved holders vote with their share count from the saved snapshot.

The execute action saves the vote result. It does not sell the island or send money. It does not carry out legal terms. The owner must carry out business and legal choices under the trust terms.

## 11. Risks

1. **Property market:** Values and rent can change with the wider economy.
2. **Laws:** Rules for digital island interests may change.
3. **Technology:** Contracts may have faults. The blockchain may stop or face attacks.
4. **Resale:** Shares may be hard to sell. Property is less easy to sell than many other assets.

## 12. Legal rules and checks

### 12.1 The planned trust and REIT structure

The plan describes a REIT-like trust under U.S. law. A REIT is a real estate investment trust. The trust keeps legal title. East Sister Rock LLC is an example of such a trust. Shares give beneficial interests in that trust.

The first plan discussed a REIT trust and an **April 2025** start. These are old plan details. They do not prove filings. They do not allow a live sale now.

The trust and its advisers must set the right legal structure. They must make the needed filings before a live sale. They must get the needed sale permissions.

The planned holder rules include the REIT **5/50 rule**. Law and identity checks must establish which limits apply. The contract checks wallets that the owner approves. It checks each wallet's share limit. It does not count all beneficial owners across wallets. It does not check the full 5/50 test on its own.

Linked wallets help track benefit use. They do not prove that the project meets legal rules.

### 12.2 Checks before purchases and transfers

The old **April 2025–April 2026** sale plan does not permit sales now. A live sale needs a confirmed cap and checked contract setup. An auditor must check the draw tool. The needed legal permissions for a sale must be in place.

Buyers need identity checks outside the contract. AML means anti-money-laundering checks. These check for unlawful use of money. KYC means know-your-customer checks. These check who a person is.

The owner approves wallets on the chain. Approval controls buying, getting and sending shares. It also controls dividend claims. The contract can block wallets that lack approval. It can block wallets that breach share limits.

The contract does not check who people are. It does not check every legal limit on holdings. Do not place ID files on the chain.

This market charges three types of saved fees. They are royalty, affiliate and marketing fees. Outside markets and plain transfers do not always charge royalty fees.

Votes record share snapshots, quorum and results. Votes do not accept or carry out a real island sale. They do not fund sale proceeds. The owner and trust must carry out legal choices and fund payments.

Current island and trust records must establish legal title and beneficial rights. Beneficial rights mean rights to trust benefits. Token balances record shares on the chain. They do not prove title on their own. They do not prove rights a court will enforce.

### 12.3 Legal and tax review

Small island interests may count as securities. U.S. law sets this status. Securities are investments that may need special sale permissions. The trust and its advisers must get needed filings and approvals. They must get any needed exemptions. Exemptions are allowed exceptions to the rules. Approval of a wallet does not prove that the project meets the law.

The trust will ask lawyers and tax experts about holder taxes. It will use certified public accountants, also called CPAs. Questions include capital gains, **1031 exchanges** and other island taxes. Capital gains are gains from selling an asset. A 1031 exchange needs expert tax advice.

The contract controls share records and transfers. The trust keeps formal legal records. Courts and rule makers can rely on the trust terms.

Chain records do not settle whether rights can be enforced in court. They do not prove that legal rules are met. Owner controls, team duties and trust terms still matter. The live sale needs outside legal review.

### 12.4 Steps before a live sale

1. Confirm the cap, trust rights and sale permissions.
2. Check the contract setup. An auditor must check the draw tool.
3. Get current advice on law and tax. Make the required filings.
4. Check identities outside the contract.
5. Approve wallets and set each wallet's share limit.
6. Record each proposed plan and vote result. Use the saved share counts.
7. Carry out island choices. Make reports and fund payments.

The old schedule is not a checked rule or deadline. The contract provides records and controls. Outside reviewers must still check law, safety and real-world duties. The island team must carry out those duties.

## 13. Project plan

The project aims to share rights to island benefits through ERC-1155 shares. Holders may receive rent and gains from a rise in value. Member perks and random boosts add stay, rent or event rights. The app records income, votes and contract use.

### Planned next steps

- Finish the app tools for reports, claims and member levels.
- Obtain outside contract security audits.
- Teach new buyers how shares and perks work.
- Plan the secondary market start.
- Start the required REIT process and filings in line with the sale plan.

## 14. Insurance and storm risks

These claims come from the island team or the earlier plan. They need current records to support them. This review does not check them on its own.

### 14.1 Storm plans and building work

The island sits in an area with hurricane risk. The plan describes major past storms, including **Hurricane Katrina**. It describes rebuilding after storms.

#### Raised foundations

The owner reports that the main home stands on reinforced pilings. Pilings are supports that raise the house above the ground. The design aims to resist storm surge, the rise of sea water during a storm.

In rare **Category 4–5 hurricanes**, fill around the supports may wash away. The plan says the raised home stays mostly unharmed. Current building records must support that claim. Engineering records must also support it.

The owner reports skill in replacing soil after storms. Dredging moves sand, silt and rocks from around the island. Workers put this fill beneath the house and around the shore.

#### Reported structural work

The plan says workers rebuilt the pilings in the prior year. They made them thicker and stronger. They addressed concrete spalling from rusting rebar. Spalling means concrete that cracks or breaks away. Rebar is steel inside concrete.

The owner says newer engineering improves storm strength. The owner says it meets or exceeds current building codes. These claims need up-to-date records.

#### Reported 50-year history

The plan describes **five decades**, or 50 years, of storms and repairs. It says repairs led to later upgrades. It describes the owners' repeated work to restore the island after severe damage.

Past repairs do not promise a future result.

### 14.2 Insurance and loss plans

The owner reports insurance for the home and key island buildings. The plan says the home has full repair or replacement cover. It says this covers any natural disaster. Actual cover depends on current policies and their limits.

#### Property insurance

The planned all-risk cover usually includes wind, storm surge and floods. It usually covers harm to the buildings. Policy terms address full or part loss. They cover named storms and other natural events.

After severe or total damage, the insurer would pay. The policy terms would set the amount. Its limits would apply too.

#### Holder rights after a loss

If total loss means the island cannot be rebuilt, the insurer would pay the trust. Holders would get their share of net insurance funds under their trust rights. These are beneficial interests, or rights to trust benefits. Policy deductibles and other costs reduce those funds. A deductible is the amount the policy does not pay.

If the ownership group chooses to rebuild, insurance would fund that work. Votes would address extra money needed or money left over. See Section 10.

#### Decisions and updates

After major damage, holders would likely vote on key choices. They may choose to rebuild now. They may keep funds until conditions improve. The vote rules set the majority needed.

The owner and admin team would post timely news in the app. The news would cover claims, repair dates and the expected effects on funds.

### 14.3 Risk plan

The plan relies on raised supports and building work. It relies on insurance and past repairs. It calls for news to holders and votes after major damage.

These plans aim to protect holders' interests. They do not remove storm, funding or legal risks. Current policy records must support the island team's claims. Current engineering records must also support them.

## Contacts and resources

- **Site:** [FloridaIsland.com](https://floridaisland.com). This is a planned link.
- **Smart contract:** The plan calls for release after the final audit.
- **News and talks:** Join the mailing list for sale and app news.

This white paper gives information only. It is not advice about money, law or investments. It is not an offer to buy or sell securities. Ask licensed experts about law, tax and money before you take part.
