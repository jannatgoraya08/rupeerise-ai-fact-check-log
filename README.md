# rupeerise-ai-fact-check-log
Fictional FinTech case study: fact-checking an AI-written investor brief against RBI and NPCI sources. Compares Claude and ChatGPT, logs hallucinations, checks Perplexity citations and ends with a guide to using AI safely in finance.
A FinTech case study on catching AI hallucinations before they reach investors.

Author: Jannat Goraya · BBA (FinTech), Chitkara Business School · Tools: ChatGPT, Perplexity · November 2026

The case

RupeeRise (fictional) is a digital lending app in Bengaluru. Its founder asked AI to write an investor brief on India's digital lending and UPI market and wanted to send it as it was. As a Business Analyst, I checked every claim against official sources before it could reach investors.

What I did
Step	Task	Tool
1	Generated the same brief in two AI tools	Claude, ChatGPT
2	Scored both drafts on 5 criteria	Manual
3	Listed 15 claims and asked the AI to rate its own confidence	AI + manual
4	Verified every claim against RBI, NPCI and PIB	Official websites
5	Opened every source Perplexity cited	Perplexity
Results
Metric	Result
Claims checked	15
Correct	12
Outdated / Distorted / Fabricated / Unsupported	0 / 1 / 0 / 2
Rated "High confidence" by AI but wrong	1
Perplexity citations that fully supported the claim	3 of 3
Tool comparison score (Claude vs ChatGPT, /10)	8 vs 6
Worst error I found

C14: the brief said a large digital user base lowers the cost of reaching customers. UPI statistics only show payment volumes and user numbers; no official source shows that RupeeRise's customer-acquisition cost would fall. An investor could treat this as proof of strong unit economics when it is only an assumption.

My top 3 "What not to do" rules
Do not quote a number without its reporting date and exact wording (evidence: C06, where "over 703 banks" did not match the PIB figure of exactly 703 as of March 2026).
Do not present assumptions as facts (evidence: C14, the claim that a large user base lowers acquisition cost).
Do not invent company costs or performance (evidence: C15, compliance costs with no RupeeRise-specific figure).
My answer to the founder

No, not as it is. The UPI and RBI facts mostly checked out, but the bank count did not match the official figure and the claims about lower acquisition cost and higher compliance cost have no evidence. Date every statistic, remove or label the unsupported claims, and confirm RupeeRise's regulatory status before sending.

Skills shown

AI output evaluation · Fact-checking with official sources · Hallucination detection · Citation analysis · Responsible AI in finance · FinTech domain knowledge

What I learned
AI writes confident, fluent text even when facts are wrong, outdated or made up.
Exact numbers, circular numbers, quotes and sources are where AI makes the most mistakes.
AI's own confidence rating is not proof; only an official source is.
A cited link is not proof either: it must be opened and must actually support the claim.
Different AI tools give different answers to the same prompt, so tools must be compared fairly.
For Indian finance, the official sources are RBI, NPCI, PIB and company reports.
Nothing AI-written should reach investors or customers without a human check.

RupeeRise and the brief in this project are fictional and created for learning.
