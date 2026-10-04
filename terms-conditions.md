# **Florida Island Tokenization – Terms and Conditions**

**Version:** 2 — corrected allocation and implementation review; supersedes conflicting 25% base-allocation wording. The initial offering cap and any additional property-sale bonus require confirmation before a live offering.

The default engineering review configuration uses 1,000 shares. Statements about title, insurance, condition and regulatory structure are operator assertions requiring current supporting documents; this implementation review does not verify them or establish legal enforceability.

These Terms and Conditions (“Terms”) govern your participation in the fractional ownership of a private island in Marathon, Florida (“East Sister Rock Island” or “the Property”) through the purchase and holding of ERC-1155 tokens (“Tokens”). By purchasing, holding, or otherwise transacting in the Tokens, you (“Token Holder” or “Participant”) agree to abide by the Terms set forth below. If you do not agree to these Terms, do not participate in the Token offering.

---

## **1. Overview**

1.1 **Tokenization**

-   Each delivered ERC-1155 share represents a fixed 0.020% base beneficial property interest. At 1,000 delivered shares the aggregate is 20%; at 4,000 it is 80%. The contract supports a deployment-selected cap from 1,000 through 4,000; the initial offering cap is not yet confirmed. A separate rental-income benefit does not add property ownership.
-   Each Token confers certain rights to its Holder, including a share in the Property’s monthly rental income and a share in future sale proceeds.

    1.2 **Scope of Ownership**

-   Legal title to the Property is held in a trust or similar entity (“the Trust”), which remains recorded in Monroe County, Florida.
-   Tokens represent _beneficial_ or _economic_ interests in the Trust; they do not grant direct legal title to the real estate or managerial authority over the Trust.

    1.3 **Use of Proceeds**

-   Capital raised from the Token offering may be used to maintain, upgrade, or operate the Property, as outlined in the accompanying White Paper.
-   The Trust may withhold a portion of revenues (e.g., for ongoing maintenance, taxes, or fees) before distributing dividends to Token Holders.

---

## **2. Token Acquisition and Sale**

2.1 **Purchasing Tokens**

-   A live sale period requires a confirmed offering cap, verified deployment and audited randomness adapter. The original April 2025 target is historical planning material. Participants use supported EVM wallets, subject to operator eligibility review and applicable AML/KYC requirements.
-   The original proposal used a \$4,500 USD initial price. The contract's current configured price is payable in ETH; stablecoin purchase support is not implemented. An owner-set USD price converts once through a verified fresh ETH/USD feed and does not remain continuously pegged to USD.

    2.2 **Secondary Market**

-   Approved wallets may list delivered units on the integrated marketplace or transfer them peer-to-peer within the configured wallet limit.
-   Integrated paid listings and offers apply their captured fee terms. ERC-2981 advertises external marketplace royalties, whose payment cannot be forced by this contract. Plain peer-to-peer transfers do not automatically pay royalties.

    2.3 **Transfer Restrictions**

-   The owner configures a per-wallet delivered-plus-pending share limit. That limit does not aggregate beneficial owners across wallets and does not independently enforce REIT “5/50” requirements.
-   Required AML/KYC review is performed outside the contract. The owner attests wallet approval on chain; the contract gates purchases, delivery, transfers and dividend claims using that approval. No names or identity documents are published by the dApp.

    2.4 **No Guarantee of Profit**

-   Purchasing Tokens involves inherent risks, including but not limited to real estate market volatility, regulatory changes, and technology risks.
-   There is no assurance that the Token value will increase, that dividends will be paid continuously, or that any future sale will occur at a profit.

---

## **3. Rental Income and Dividends**

3.1 **Monthly Rental Income**

-   The original proposal used approximately \$100,000 USD monthly rental income (including special events) as planning material. It is not a verified current income statement or a guaranteed return; dated owner reports and underlying operator records must be reviewed.
-   Actual monthly income may fluctuate due to market demand, maintenance downtime, force majeure events, or other factors.

    3.2 **Distribution Mechanics**

-   **Base Dividend Allocations**: Every delivered share receives 0.020% of whole-property net rental income. Unissued shares do not enlarge another holder's allocation. At 1,000 delivered shares the collective base allocation is 20% of net rental income, separate from the gross-income revenue benefit.
-   **Quarterly Payout**: Dividends are typically disbursed quarterly to reduce administrative costs and gas fees.
-   **Withdrawal**: Token Holders must connect their wallets via the Project’s dApp and initiate a “Withdraw” transaction to claim accrued dividends.

    3.3 **Revenue Boost Tokens**

-   Five units are randomly assigned Revenue Boost status across the deployment-selected cap. Each delivered revenue-benefit unit receives an additional 1% of whole-property gross rental income; all five collectively receive 5%. Each retains its ordinary 0.020% base property and net-rental rights. The benefit is additional income, not additional equity. If a benefit unit is not delivered, its allocation is not redistributed to another holder.
-   The owner must supply real ETH funding for these allocations. Reports do not fund dividends automatically. The funding transaction checks expected delivered base/revenue counts and exact payment; previously accrued dividends remain with the account entitled at deposit after a transfer. Bare ETH receipts do not create a dividend round.

---

## **4. Island Stay and Membership Tiers**

4.1 **Island Stay Boost**

-   One randomly assigned stay-benefit unit entitles its eligible holder to a two-night stay per UTC service-start year, subject to owner confirmation. The registry permits one confirmed collection-wide stay per year; pending reservations consume availability until cancelled or confirmed.
-   Subject to availability and scheduling; black-out dates or certain restrictions may apply.

    4.2 **Membership Tiers**

-   Tiers use delivered shares in a single wallet: 1–25 gives 10% off one seven-night week; 26–50 gives 20%; 51–100 gives 40%; 101+ gives one free seven-night week per UTC service-start year. Linked/recovery wallets in an owner-attested opaque identity group share one annual membership use. Wallets cannot be rebound to reset usage. No personal identity information is published by this grouping.
-   Token Holders are responsible for making timely reservations via the official dApp interface.
-   Five event-benefit units grant 15% off each distinct active owner-published event for up to 40 invited guests, without an annual event-count limit. Each verified identity group may use one discount per distinct event.
-   Requests reserve quota; only pending cancellation releases it. Confirmation checks current eligibility/holdings and consumes quota. An on-chain confirmation is operator acceptance, not proof of physical service, accommodation payment, title or legal identity. Availability and fulfillment remain operator responsibilities.

---

## **5. Governance and Voting**

5.1 **Operational Control**

-   The Trust (or Project Owner) retains primary authority over daily operations, maintenance, and improvements.
-   Significant decisions (e.g., property sale, major capital expenditures) may be put to a vote, subject to governance modules in the smart contract.

    5.2 **Voting Rights**

-   Each Token generally represents one vote, unless otherwise specified by the governance model.
-   A threshold majority (defined by the Trust or governance documents) is required to approve major decisions.
-   Certain regulatory constraints (e.g., REIT compliance) may override or limit on-chain voting outcomes.

---

## **6. Future Sale and Liquidation**

6.1 **Property Sale**

-   Each delivered share's base beneficial interest is 0.020% of net sale proceeds after liens, costs and taxes, subject to the governing trust agreement. At 1,000 shares that collective base interest is 20%, not 25%.
-   An additional sale-proceeds bonus for revenue-benefit units remains conditional on an explicit owner/trust decision. The 5% gross rental-income benefit does not automatically apply to a property sale. No additional sale-bonus funding is enabled by default.
-   The owner may fund the documented base sale allocation from operator-attested net proceeds: net proceeds × delivered shares ÷ 5,000, with whole-wei rounding and no additional bonus pool until confirmed. The funding transaction checks delivered base/revenue counts and requires the owner's exact ETH payment. It creates funded claims without executing a deed transfer, verifying the property sale or settling the trust's legal obligations.

    6.2 **Forced Sale or Buyout**

-   Under certain conditions (e.g., unanimous or threshold vote, eminent domain, significant damage), the Trust may be compelled to sell or repurchase the Property.
-   Token Holders will be notified through the dApp and given instructions on collecting their share of proceeds.

---

## **7. Insurance and Disaster Recovery**

7.1 **Insurance Coverage**

-   The Trust maintains all-risk property insurance. Coverage typically includes hurricane damage, wind damage, flood, and other named storm events, subject to policy limits and deductibles.
-   In a total loss scenario where rebuilding is deemed infeasible, insurance proceeds are disbursed to the Trust, then proportionally distributed to Token Holders.

    7.2 **Hurricane Resilience**

-   The main residence is built on reinforced pilings, designed for elevated storm surge resistance.
-   Post-storm procedures (e.g., dredging) restore displaced sand. Recent engineering upgrades address concrete spalling and strengthen the foundation.

    7.3 **Rebuilding Contingencies**

-   If a catastrophic event partially damages the Property, the Trust may decide to rebuild using insurance proceeds.
-   Token Holders may vote on allocating additional capital for large-scale repairs if insurance is insufficient.

---

## **8. Regulatory and Compliance**

8.1 **REIT Compliance**

-   The Project intends to structure its offering to align with U.S. REIT rules, including but not limited to ownership caps (the “5/50 rule”) and formal registration with the IRS.
-   The trust and its advisers must establish the applicable structure, filing requirements and current offering schedule; historical dates do not authorize a live offering.

    8.2 **Securities Laws**

-   Tokens may be deemed securities under relevant securities laws. The Project, or its authorized entity, shall undertake necessary registrations, exemptions, or filings.
-   Participants may need to meet accreditation or other qualification requirements, depending on regulatory conditions.

    8.3 **AML/KYC**

-   All Participants must pass AML/KYC checks prior to purchasing Tokens or receiving dividends.
-   The Project reserves the right to reject or freeze transactions that fail compliance checks.

---

## **9. Risk Factors**

9.1 **Real Estate Market Volatility**

-   The Property’s value and rental income are subject to broader economic, tourism, and market conditions.

    9.2 **Technological Risks**

-   ERC-1155 smart contracts may contain vulnerabilities. Although the Project plans audits and best practices, the risk of hacks, exploits, or blockchain downtime remains.

    9.3 **Liquidity**

-   There is no guarantee that a robust secondary market will develop. Reselling Tokens may be challenging or subject to significant discounts.

    9.4 **Regulatory Changes**

-   Future laws or regulations could impact the Project’s operations, the compliance framework, or Token trading activity.

---

## **10. Disclaimers**

10.1 **No Investment Advice**

-   Nothing in these Terms, the White Paper, or the Project’s communications should be construed as financial, legal, or tax advice. Consult licensed professionals before participating.

    10.2 **No Guarantee of Returns**

-   Past performance or Property history does not guarantee future outcomes. Holdings may lose value.

    10.3 **Force Majeure**

-   The Project is not liable for any failure or delay caused by events beyond its reasonable control, including acts of God, natural disasters, war, or governmental action.

---

## **11. Governing Law and Dispute Resolution**

11.1 **Governing Law**

-   These Terms are governed by and construed in accordance with the laws of the State of Florida, without regard to conflict-of-law principles.

    11.2 **Venue**

-   Any disputes arising out of or in connection with these Terms shall be exclusively brought in the state or federal courts located in Monroe County, Florida.

    11.3 **Arbitration** _(If Applicable)_

-   The Trust may require binding arbitration for certain disputes, as further detailed in a separate arbitration agreement or addendum.

---

## **12. Amendments and Updates**

-   The Project reserves the right to modify or update these Terms at any time to reflect changes in business operations, regulatory requirements, or market conditions.
-   Any material updates will be posted on the Project’s official website and, where possible, communicated via the dApp or community channels.

---

## **13. Acceptance**

By purchasing, holding, or transferring Tokens, you acknowledge that you have read, understood, and agreed to these Terms and Conditions. If you do not agree to these Terms, you must refrain from participating in any Token transactions associated with Florida Island Tokenization.

---

### **Contact Information**

For more information, inquiries, or to request a copy of these Terms, please visit:

-   **Website**: [FloridaIsland.com](https://floridaisland.com) _(Placeholder link)_
-   **Community**: Join our mailing list for official updates and community discussions.

> **Disclaimer**: This Terms and Conditions document is provided for informational purposes. It is not intended to supersede any legal documentation filed with regulatory authorities or the trust’s governing agreement. In case of discrepancies, official filings and trust agreements prevail.
