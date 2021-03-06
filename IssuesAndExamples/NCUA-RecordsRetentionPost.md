# Summary

**Blockchains for Data and Record Preservation**

The burden of storing data is getting less and less costly.  However, to meet record retention legal requirements it can also be important to prove that the record has not been changed or otherwise tampered with since the time is was stored.  Hash algorithms are capable of proving "message integrity".  Therefore, by storing the hash digests of electronic records on a publicly verifiable, globally accessible blockchain and maintaining a copy of the full records in low cost "off-chain" (traditional) data storage, it is possible, in principle, to provide a long term records archive.  Naturally, adequate  logs and other controls must be maintained about the business and legal records linking the hash digests entered onto a blockchain and the data files in storage to prove provenance.  This combination could save money and reduce other burdens of ensuring long term records and data preservation.  

# Example

**US Federal Credit Union Example**

The National Credit Union Administration ([NCUA](https://www.ncua.gov)) governs US Federal Credit Unions.  The [NCUA](https://www.ncua.gov) formal guidance for [federally-insured credit unions](https://www.ecfr.gov/cgi-bin/text-idx?SID=21ab23ef124e366686e46d1e1bcef3e9&mc=true&node=se12.7.749_10&rgn=div8) contained in Part [749](https://www.ecfr.gov/cgi-bin/text-idx?SID=21ab23ef124e366686e46d1e1bcef3e9&mc=true&tpl=/ecfrbrowse/Title12/12cfr749_main_02.tpl) of [NCUA's](https://www.ncua.gov) regulations is not terribly prescriptive. 

According to 12 CFR §749.4 (covering the "format for vital records preservation"):

> Preserved records may be in **any format that can be used to reconstruct the credit union’s records**. The format used must **accurately reflect the information in the record, remain accessible to all persons** entitled to access by statute, regulation or rule of law, and be capable of reproduction by transmission, printing, or otherwise. (emphasis added) [See: [72 FR 42273, Aug. 2, 2007](https://www.ncua.gov/Legal/Regulation%20History/749F-72fr42271.pdf)] 

Given the format requirements are (appropriately) flexible, the requirement that a Credit Union provide a method to "accurately reflect the information in the record" could be satisfied by use of a system combining low cost bulk data storage while ensuring date/time and message integrity with hash digests of individual records and sets of records (ie in trees) on public blockchains.  If such a record management plan were approved by the regulator it could in fact be easier and faster to for examiner, auditors and others to use and rely upon.  

In fact, [NCUA](http://nafcucomplianceblog.typepad.com/nafcu_weblog/2016/07/oldie-but-goodie-record-retention-.html) notes first the importance of following applicable state law under [Appendix A](https://www.ecfr.gov/cgi-bin/text-idx?SID=21ab23ef124e366686e46d1e1bcef3e9&mc=true&node=ap12.7.749_15.a&rgn=div9) to Part 749 in determining how long to keep particular records:

> 1. What Are the Recommended Minimum Retention Times?

> Record destruction may impact the credit union's legal standing to collect on loans or defend itself in court. Since each state can impose its own rules, it is prudent for a credit union to consider consulting with local counsel when setting minimum retention periods. A record pertaining to a member's account that is not considered a vital record may be destroyed once it is verified by the supervisory committee. **Individual Share and Loan Ledgers should be retained permanently**. Records, for a particular period, should not be destroyed until both a comprehensive annual audit by the supervisory committee and a supervisory examination by the NCUA have been made for that period. (Emphasis added.) 

NCUA guidance notes that certain other records should also be retained permanently, including:

*   The FCU’s charter, bylaws and amendments to these documents
*   Minutes of membership meetings and meetings of the board, credit committee and supervisory committee
*   Copies of the FCU’s call report (NCUA Form 5300 or 5310) and the Credit Union Profile Report (NCUA Form 4501) or its equivalent
*   One copy of each supervisory committee annual audit report and attachments
*   Supervisory committee records of account verification
*   Journal and cash record
*   General ledger
*   Copies of periodic statements or the individual share and loan ledger (meaning, “a complete record of the account should be kept permanently)
*   Bank reconcilements
*   Listing of records destroyed

Part 749 also addresses vital records preservation and can be helpful when reviewing recordkeeping policies and procedures.

From a federal regulatory perspective, specific rules often have their own record retention provisions. Here are some examples:

Regulation Z addresses record retention in [section 1026.25](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3Dbc8649c04194e4b989a32c5c6cbf76fb%26mc%3Dtrue%26node%3Dse12.9.1026_125%26rgn%3Ddiv8&sa=D&ust=1498356573029000&usg=AFQjCNFvojbznDVAF5_SRgX3KOCoJ7PU3Q). The rule contains a general 2 year record retention requirement, with some longer retention periods for other specific documents. For example, there is a three year record retention requirement for information relating to loan originator compensation and the ability to repay/qualified mortgage rule. For loans subject to TRID, credit unions must retain evidence of compliance for three years, but all Closing Disclosures, including revised Closing Disclosures, must be retained for five years post-consummation.

Regulation B has a [particular records retention rule](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3D600feb2e3758a854a2f0ae0a3dbc570a%26node%3D12:8.0.2.8.2.0.1.12%26rgn%3Ddiv8&sa=D&ust=1498356573030000&usg=AFQjCNFWSmWCHzv32rSObxAikQw6vUDrfA) found in §1002.12 and [a requirement](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3D600feb2e3758a854a2f0ae0a3dbc570a%26node%3D12:8.0.2.8.2.0.1.12%26rgn%3Ddiv8&sa=D&ust=1498356573030000&usg=AFQjCNFWSmWCHzv32rSObxAikQw6vUDrfA) to keep in the application file a copy of any written notice that was required to be mailed under the regulation. There are more specific requirements relating to business credit, keeping records longer if the credit union knows it is under investigation by a regulator or state’s attorney general, and requires credit unions to keep records relating to prescreened offers of credit for 25 months so it may be worth reviewing in full. The [rule’s commentary](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/retrieveECFR?gp%3D%26SID%3D6852755b7981b2799ab8716d46c243ab%26mc%3Dtrue%26n%3Dpt12.8.1002%26r%3DPART%26ty%3DHTML%23ap12.8.1002_116.1&sa=D&ust=1498356573031000&usg=AFQjCNGAIbQX_C8AbnQn6xaQGwed-mE-5A) discusses keeping computerized records of notice.

Bank Secrecy Act. The BSA/AML examination manual contains an [appendix on record retention requirements](https://www.google.com/url?q=https://www.ffiec.gov/bsa_aml_infobase/pages_manual/OLM_116.htm&sa=D&ust=1498356573032000&usg=AFQjCNH7leOydkxZLMykMMBwuI0JdhGHpA). Some records must be kept for 5 years, such as purchases of monetary instruments or funds transfers of $3,000 or more (although there are some exceptions here). Records under the credit union’s customer identification program (CIP) must be retained for five years after the account is closed.  Other BSA provisions are not subject to a specific record retention timeframe. However, to ease compliance, many credit unions keep all BSA-related records for 5 years rather than having to sort out which items are specifically required to be kept for 5 years and which are not.

Other federal rules. Here are a few other federal regulations with specific recordkeeping provisions:

*   Regulation E, [section 1005.13(b)](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3D5c21e9520c115b43c457d935b797c162%26mc%3Dtrue%26node%3Dse12.8.1005_113%26rgn%3Ddiv8&sa=D&ust=1498356573034000&usg=AFQjCNGZeO5u7SOcXpoEvcNL7OeDBOXIAg) (generally, two years from the time of providing disclosures)
*   Truth in Savings, [section 707.9(c)](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3D38782dc7540b51e0cff68fa18853e1ea%26mc%3Dtrue%26node%3Dse12.7.707_19%26rgn%3Ddiv8&sa=D&ust=1498356573034000&usg=AFQjCNFYgj7HvmSdIToMoo76scBcBwMc-w) (generally, two years from the time of providing disclosures)
*   Regulation X contains a few recordkeeping requirements. One example relates to mortgage servicing under RESPA, located at [section 1024.38(c)](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3Dc530b0589374a53443fea0a2bd16dc5e%26mc%3Dtrue%26node%3Dse12.8.1024_138%26rgn%3Ddiv8&sa=D&ust=1498356573035000&usg=AFQjCNEQoQWZqe9RnuZTnqy0bn4gO0fDBg) (generally, until one year after the date a mortgage is discharged or servicing is transferred to another servicer). Other provisions have a five year retention period.
*   Regulation C, [section 1003.5(d)](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3D5b5cc0b48c152d95cecafa127850a56e%26mc%3Dtrue%26tpl%3D/ecfrbrowse/Title12/12cfr1003_main_02.tpl&sa=D&ust=1498356573036000&usg=AFQjCNEyq2cBqsCLoR9aWppFOrxkCqcUbQ) (modified register must be available to the public for 3 years, and the disclosure statement for 5 years
*   Regulation CC, funds availability, [section 229.21(g)](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3Dbd8af386a18b43338445768cb7786a4b%26mc%3Dtrue%26node%3Dse12.3.229_121%26rgn%3Ddiv8&sa=D&ust=1498356573037000&usg=AFQjCNE6ioOzv1BtQQmDQUWiRlG5YzpWeQ) (generally, at least two years)
*   Fair Credit Reporting Act/Regulation V – [Section 615(d)(3)](https://www.google.com/url?q=https://www.consumer.ftc.gov/sites/default/files/articles/pdf/pdf-0111-fair-credit-reporting-act.pdf&sa=D&ust=1498356573038000&usg=AFQjCNHcRG1pYcCRS0hrI3CFLXRr1gbhcg) requires credit unions to retain records relating to prescreened offers of credit for three years. Additionally, [Appendix E](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3Dbb0d71f7d659810a1728672cd3393843%26mc%3Dtrue%26node%3Dap12.8.1022_1140.e%26rgn%3Ddiv9&sa=D&ust=1498356573038000&usg=AFQjCNHe94VE1pxhQOno0TBckjMma4-w4w) of Regulation V contains guidelines on the accuracy and integrity of data reported to consumer reporting agencies (“Maintaining records for a reasonable period of time, not less than any applicable recordkeeping requirement, in order to substantiate the accuracy of any information about consumers it furnishes that is subject to a direct dispute…”)
*   [Flood insurance](https://www.google.com/url?q=http://www.ecfr.gov/cgi-bin/text-idx?SID%3D3a7187a9c99972eaf6f56ba24ad008e0%26mc%3Dtrue%26node%3Dse12.7.760_19%26rgn%3Ddiv8&sa=D&ust=1498356573039000&usg=AFQjCNGviibqRm2Ve0dNtAYBiEFITd5e2Q) (record of receipt of the notice of special flood hazards and availability of flood insurance must be kept for as long as the credit union owns the loan)
*   IRS Form 1099 (generally 3 years from the reporting due date, but four years for federal withholding information and filings under Form 1099-C for cancellation of debts, see p. 13 of [this guide](https://www.google.com/url?q=https://www.irs.gov/pub/irs-pdf/p1220.pdf&sa=D&ust=1498356573040000&usg=AFQjCNEABwDMKDpO089MrjIMcDoUrPSV1A). The IRS [generally requires](https://www.google.com/url?q=https://www.irs.gov/publications/p15/ar01.html%23en_US_2016_publink1000294375&sa=D&ust=1498356573041000&usg=AFQjCNE3Ghid5Hqa1UuSOZIIizQzD6bByA) that employment tax records are kept for four years.


