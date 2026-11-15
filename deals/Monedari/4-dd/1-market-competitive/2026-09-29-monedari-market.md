# Monedari: Market analysis

| | |
|---|---|
| Stage | Pre-IC |
| Date | 2026-09-29 |
| Prepared by | market-analysis agent, for Example Ventures |
| Status | Pre-IC, initial, 2026-09-29 |

## One-page summary

| Layer | Figure | Unit and year | Logic |
|---|---|---|---|
| TAM | USD 102.6M | Net revenue pool per year, 2026 prices | 1,103,000 neighborhood grocery shops in Mexico (653,000) and Colombia (450,000) x USD 93 realized net revenue per shop per year |
| SAM | USD 78.4M | Net revenue pool per year, 2026 prices | 842,500 shops left after the bank-account gate (Mexico 63.0%, Colombia 95.8%) x USD 93. Mexico USD 38.3M is revenue-ready today. Colombia USD 40.1M depends on a local card acquirer that is not signed |
| SOM bear (3%) | USD 2.35M | Net revenue per year | 3% of SAM, about 25,300 shops |
| SOM base (5%) | USD 3.92M | Net revenue per year | 5% of SAM, about 42,100 shops |
| SOM bull (8%) | USD 6.27M | Net revenue per year | 8% of SAM, about 67,400 shops |

- **Market growth:** about 10% to 14% a year for the revenue pool (INFERRED). Mexican card payments grew 14% in 2025, but sales at Mexican and Colombian shops are flat to falling.
- **Bottom-up cross-check:** USD 6.06M by 2031 (65,200 shops), or USD 4.73M from Mexico alone. This sits between the base and bull cases, so the two methods agree at the top of the band. The bottom-up assumes the current pace of new shops holds, which is generous.
- **Reality test: FLAG, needs a conviction discussion.** A 10x return needs USD 50M revenue at exit (4x revenue PLACEHOLDER multiple). That is 64% of today's SAM at current revenue per shop, and 33% of SAM even at the USD 179 per shop the deck's 2029 plan implies. Card payments at neighborhood shops cannot carry the return by themselves.
- **Open questions that matter most:** (1) can Adelanto and Monedari Plus lift revenue per shop well above USD 93; (2) when will a Colombian card acquirer be signed, given that half the SAM depends on it; (3) why does the deck count 1.2 million Mexican shops when the census counts about 653,000.

## Scope and method

**Sizing follows realistic geography.** Monedari runs only in Mexico (12,900 active merchants) and Bogota (1,300, QR only) (call notes, 2026-09-22). Both TAM and SAM are limited to these two countries. Peru, Ecuador and Central America also have neighborhood-shop channels, but Monedari has no operations, no acquirer and no plan for them in this round (deck slide 15), and none was sized with sourced data, so they are excluded. Brazil is excluded because it has a different language and payment rails (Pix), different regulation, and incumbents that are already entrenched. The deck's "5 million small shops in Latin America, a USD 12B market" (deck slide 6) has no source and no definition, so it is not used.

**The price basis is Monedari's realized revenue per shop.** September 2026 net revenue was USD 100K a month (deck slide 8). Colombia is QR only, and QR is free to the merchant (deck slide 7, call notes), so this analysis treats Colombian revenue as close to zero (INFERRED, consistent with the pre-screen). USD 100K / 12,900 Mexican merchants = USD 7.75 a month = USD 93 a year per revenue-generating shop. That figure covers card take, Monedari Plus and Adelanto at today's attach rates. It is a company figure, not independently confirmed. The blended figure across all 14,200 merchants is USD 7.04 a month (USD 84.5 a year).

**Revenue per shop is cross-checked against card volume.** Card volume per merchant is USD 9.8M x 62% / 14,200 = USD 428 a month, and at a 1.17% net take that gives USD 5.01 a month of card revenue (deck slides 7, 8). Monedari charges 3.2% + IVA. Clip lists 3.6% + IVA and Mercado Pago Point 3.5% + IVA ([Tiendanube](https://www.tiendanube.com/blog/mx/cual-es-la-mejor-terminal-punto-de-venta-mexico/), [Mercado Pago](https://www.mercadopago.com.mx/herramientas-para-vender/lectores-point?matt_tool=85113909)), so Monedari's price sits below the market's list prices, not above them.

**A mature revenue per shop is shown as a sensitivity.** The deck's plan reaches USD 21M net revenue in 2029 with 85,000 merchants at the end of 2028 and 150,000 at the end of 2029 (deck slide 14). USD 21M divided by the average of 117,500 merchants is about USD 179 per shop per year. That is the company's own projection of where Adelanto and Monedari Plus take revenue per shop. It is used only as an upper sensitivity, never as the base.

## TAM, SAM and SOM

### Top-down step-down

| Step | Mexico | Colombia | Total |
|---|---|---|---|
| Macro pool | 5,468,180 economic units, 95.4% micro (2023) | About 1.25M commercial establishments (INFERRED) | n/a |
| Startup's target: neighborhood grocery shops | 653,000 (INFERRED, 2023) | 450,000 (2024 to 2025) | 1,103,000 |
| TAM revenue pool at USD 93 per shop per year | USD 60.7M | USD 41.9M | USD 102.6M |
| Structural gate: owner has a formal account | 63.0% | 95.8% | n/a |
| Gated, addressable shops | 411,400 | 431,100 | 842,500 |
| SAM revenue pool at USD 93 per shop per year | USD 38.3M | USD 40.1M (depends on an acquirer) | USD 78.4M |

**Macro pool, Mexico.** INEGI's 2024 Economic Census (reference year 2023) counts 5,468,180 private-sector economic units, and 95.4% of them employ 0 to 10 people ([INEGI CE 2024 results report](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2025/ce/CE2024_def_RR.pdf)). The census covers only establishments with fixed premises. It excludes street vendors and stalls that are not permanently anchored.

**The target count is derived from census growth data.** The census report does not print the national count of grocery shops (the census category "tiendas de abarrotes, ultramarinos y misceláneas"). It does say that grocery shops added 81,500 units between 2018 and 2023, at a compound annual growth rate of 2.7%, more than any other activity in the country. Working backward: 1.027^5 = 1.1425, so the 2018 count is 81,500 / 0.1425 = about 572,000 and the 2023 count is about 653,000 (INFERRED). Rounding in the 2.7% rate gives a range of about 643,000 to 665,000. **The method checks out on staff numbers.** Applying the same method to staff (216,191 added at 4.1% a year) gives 1,187,800 people in 2023. The census reports 1,191,398, a difference of 0.3%. That is also 1.8 people per shop, which fits a family-run tiendita.

**The census count is half the deck's figure.** The deck claims 1.2 million neighborhood shops in Mexico (deck slide 6). The trade association ANPEC is quoted in the press at over 1.05 million ([Emprendedor](https://emprendedor.com/tiendita-emprendimiento-historia-mexico-comercio-tradicional/)). The gap is most likely shops without fixed premises, or other kinds of small store, which the census does not count as grocery shops (INFERRED). This analysis uses the official census count. The difference is an open question, because counting 1.2 million shops would raise the Mexican TAM by about 84%.

**Macro pool and target, Colombia.** The national retail federation Fenalco puts neighborhood shops (tiendas de barrio) at about 450,000 in its most recent estimates ([Semana](https://www.semana.com/economia/articulo/fenalco-expone-preocupante-panorama-sobre-ventas-en-las-tiendas-de-barrio/202447/)). It has also used 500,000, which it describes as 40% of the country's commercial establishments ([La República](https://www.larepublica.co/empresas/las-tiendas-de-barrio-son-motor-del-comercio-y-generan-mas-de-575-000-empleos-4212334)). That implies about 1.25M commercial establishments (INFERRED). Colombia has no official census count of these shops. This analysis uses the lower figure, 450,000.

### Structural gate

**Payouts require a bank account.** Onboarding asks for an ID photo and a bank account, and money lands in that account the next business day (deck slides 3, 5). A shop whose owner has no formal account cannot be paid out, so account access is the gate. No data source covers account ownership among shop owners specifically. The adult population figure is used as a proxy (INFERRED).

**Mexico: the gate removes 37%.** In 2024, 63.0% of Mexicans aged 18 to 70 had at least one formal savings account, up 18.9 points since 2015 ([INEGI ENIF 2024](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2025/enif/ENIF2024_CP.pdf)). 653,000 x 63.0% = 411,400 gated shops. The proxy may understate owners who run a business. On the other hand, ANPEC reports that 55.57% of shopkeepers had no card terminal in the second half of 2024 ([Milenio](https://amp.milenio.com/negocios/por-que-las-personas-prefieren-pagar-en-efectivo-y-no-con-tarjeta)), so most shops are still unserved by card acceptance of any kind.

**Colombia: the account gate barely bites, but card acceptance does.** In 2024, 95.8% of Colombian adults held a deposit product, largely through low-balance digital accounts ([Superintendencia Financiera, RIF 2024](https://www.superfinanciera.gov.co/publicaciones/10115642/para-2024-el-963-de-los-colombianos-adultos-tenia-al-menos-un-producto-de-deposito-o-credito/)). 450,000 x 95.8% = 431,100 gated shops. The constraint that actually binds in Colombia is different: Monedari cannot accept cards there until it signs a local acquirer (call notes). Until it does, Colombian shops generate almost no revenue. The USD 40.1M Colombian SAM is therefore counted, but flagged as contingent. It also assumes Colombian card economics similar to Mexico's, which is PENDING.

**Card demand is already priced into revenue per shop.** In Mexico, 85.2% of people pay cash for purchases of 500 pesos or less, and only 10.4% use a card ([INEGI ENIF 2024](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2025/enif/ENIF2024_CP.pdf)). This low card use is why card volume per shop is only USD 428 a month. It is reflected in the USD 93 per shop and is not applied a second time as a gate.

### SAM summary

**SAM is USD 78.4M, and only half of it is revenue-ready.** 842,500 gated shops x USD 93 = USD 78.4M a year. Mexico alone is USD 38.3M. At the plan-implied USD 179 per shop, the SAM would be USD 150.8M (Mexico USD 73.6M). For comparison, the full SAM in card volume terms is 842,500 x USD 428 x 12 = about USD 4.3B a year (INFERRED). If the deck's USD 12B were annual payment volume, 1.17% of it would be USD 140M, which is the same order of magnitude as this TAM (INFERRED reading of an undefined claim).

## SOM band

| Scenario | Share of SAM | Shops | Net revenue per year (USD 93 per shop) | At USD 179 per shop (sensitivity) |
|---|---|---|---|---|
| Bear | 3% | 25,300 | USD 2.35M | USD 4.52M |
| Base | 5% | 42,100 | USD 3.92M | USD 7.54M |
| Bull | 8% | 67,400 | USD 6.27M | USD 12.06M |

**The base case stays at 5%.** No adjustment is made, for three reasons. (1) Competition is intense and the competitors are much larger. Aggregators run 4.58M of Mexico's 6.54M point-of-sale terminals, and they added 10% in 2024 ([DPL News, citing CNBV Panorama Anual de Inclusión Financiera 2025](https://dplnews.com/?p=300279)). Mercado Pago reports more than 1 million active terminals, double its September 2024 figure ([DPL News](https://dplnews.com/?p=287818)). Banks and fintechs, including Mercado Pago, Banorte and Banco Azteca, now offer tap-to-pay, and a Visa initiative with Clip targets about 692,000 small businesses ([Expansión](https://expansion.mx/economia/2026/06/16/pagos-contactless-alcanzan-30-y-presionan-a-reducir-terminales-en-mexico)). These facts argue against going above 5%. (2) Monedari already holds 12,900 / 411,400 = 3.1% of gated Mexican shops (INFERRED), and its wholesaler channel brings shops in at USD 24 each (deck slide 10). These facts argue against going below 5%. (3) Free instant transfers (SPEI, CoDi and DiMo in Mexico, Bre-B in Colombia) compete directly with paid card acceptance and cap the price.

**The deck's plan sits far above the bull case.** 150,000 merchants by the end of 2029 (deck slide 14) would be 17.8% of all gated shops in both countries, or 36.5% of gated Mexican shops if most of them are Mexican. The plan's USD 21M is 27% of today's SAM at USD 93 per shop, or 14% at USD 179. The plan is not impossible, but it assumes more than twice the bull share.

## Bottom-up SOM

| Country | Active shops, September 2026 | Net new shops, last 12 months | Assumed net new shops per year, 2027 to 2031 | Shops in 2031 | Revenue per shop per year | Net revenue in 2031 |
|---|---|---|---|---|---|---|
| Mexico | 12,900 | 7,600 (INFERRED) | 7,600 | 50,900 | USD 93 | USD 4.73M |
| Colombia | 1,300 | 1,300 in about 6 months | 2,600 | 14,300 | USD 93 if cards go live, about 0 if QR only | USD 1.33M (contingent) |
| Total | 14,200 | n/a | n/a | 65,200 | n/a | USD 6.06M (Mexico only USD 4.73M) |

**The bottom-up extends the observed pace.** Mexico went from 5,300 active merchants in September 2025 to 12,900 in September 2026. Colombia launched in March 2026, so all 5,300 were Mexican (deck slides 8, 14, call notes). That is 7,600 net new Mexican shops a year, and this build holds that pace for five years. Colombia added 1,300 shops in about six months, which this build annualizes to 2,600. No further acceleration from the four-state expansion is assumed. There is also a reason to see the build as generous: with six-month retention at 71% (deck slide 9), churn grows as the base grows, so holding net growth flat needs rising gross acquisition.

**The two methods agree at the top of the band.** The bottom-up gives USD 6.06M and 65,200 shops (7.7% of SAM shops), against the top-down base of USD 3.92M and bull of USD 6.27M. The bottom-up is 55% above the base, but it stays inside the bull case. The gap is explained by the generous assumption above, and by Mexico reaching 12.4% of gated Mexican shops while Colombia reaches only 3.3% of its own. Both methods give the same answer to the question that matters: at today's revenue per shop, the company reaches USD 4M to 6M of net revenue around 2031. The base-case SOM to carry forward is USD 3.92M.

## Market growth

| Indicator | Figure | Period | Source |
|---|---|---|---|
| Card payments in Mexico, count | 11,261 million, +14% | 2025 vs 2024 | [Expansión](https://expansion.mx/economia/2026/06/16/pagos-contactless-alcanzan-30-y-presionan-a-reducir-terminales-en-mexico) |
| Aggregator terminals in Mexico | 4.58M, +10% | End 2024 vs end 2023 | [DPL News / CNBV](https://dplnews.com/?p=300279) |
| Cash as main payment, purchases of 500 pesos or less | 90.1% to 85.2% | 2021 to 2024 | [INEGI ENIF 2024](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2025/enif/ENIF2024_CP.pdf), [Milenio](https://amp.milenio.com/negocios/por-que-las-personas-prefieren-pagar-en-efectivo-y-no-con-tarjeta) |
| Mexican grocery shops, count | +2.7% a year | 2018 to 2023 | [INEGI CE 2024](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2025/ce/CE2024_def_RR.pdf) |
| Mexican tiendita sales | Down about 15%, about 60,000 shops at risk (ANPEC) | 2025 | [Publimetro](https://www.publimetro.com.mx/noticias/2025/10/17/ieps-ahoga-al-comercio-formal-caen-ventas-15-por-ciento-y-60-mil-tienditas-estan-en-peligro/) |
| Colombian tienda sales | 82% of shops had falling (53%) or flat (29%) sales | Second half of 2024 | [La República / Fenalco](https://www.larepublica.co/empresas/segun-fenalco-82-de-las-tiendas-aseguro-que-sus-ventas-cayeron-al-cierre-de-2024-4072546) |

**Planning range: 10% to 14% a year (INFERRED).** No source sizes this specific revenue pool. It grows when more shops accept cards and when more of each shop's sales move to cards. Those drivers move at roughly the national rate of card payments (+14%) and terminals (+10%). Pulling the other way are flat-to-falling shop sales: ANPEC links the Mexican decline to the 2026 IEPS tax increase on soft drinks and cigarettes. The 10% to 14% range is an analyst estimate for Mexico. Colombia has weaker data: only about 20% of personal payments were digital in 2024 ([BBVA Research](https://www.bbvaresearch.com/wp-content/uploads/2025/07/20250708-Columna-Bre-B_DQ.pdf)). **Growth does not close the gap.** At 12% a year for five years (1.12^5 = 1.76), the base-case SOM grows from USD 3.92M to about USD 6.9M.

## Structural tailwinds

**Contactless makes tap-to-phone viable.** Tap-to-phone works only if customers' cards and phones are contactless. Visa reports that contactless rose from 2% to 30% of in-person card payments in Mexico in about two years ([Expansión](https://expansion.mx/economia/2026/06/16/pagos-contactless-alcanzan-30-y-presionan-a-reducir-terminales-en-mexico)). The same shift lowers the barrier for competitors: banks and large fintechs now offer tap-to-pay too.

**Cash is slowly giving way to digital payments.** Formal account ownership in Mexico rose 18.9 points between 2015 and 2024, to 63.0%. Cash as the main way to pay for small purchases fell from 90.1% to 85.2% between 2021 and 2024 ([INEGI ENIF 2024](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2025/enif/ENIF2024_CP.pdf)). Card payments grew 14% in 2025. Neighborhood shops are where cash holds out longest, which is the gap Monedari targets. The same data also shows the gap closing slowly: 85% is still cash.

**The target population is growing, and non-banks serve it.** Grocery shops added more units than any other activity in Mexico between 2018 and 2023 (+81,500) ([INEGI CE 2024](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2025/ce/CE2024_def_RR.pdf)). Non-bank aggregators and acquirers now run 78.66% of Mexico's terminals, while bank terminals are shrinking ([DPL News / CNBV](https://dplnews.com/?p=300279)). Small merchants already buy acceptance from non-banks, which suits Monedari's model. The caveat is the 2025 to 2026 sales squeeze at the shops themselves.

## Market conclusion

**The payments pool is real but small.** Card acceptance at Mexican and Colombian neighborhood shops is a revenue pool of about USD 78M a year (SAM), and only USD 38M of it is in Mexico, where Monedari can collect revenue today. The company is well placed in the niche: its price is below Clip and Mercado Pago, no hardware is needed, its wholesaler channel costs USD 24 per shop, and it already holds about 3% of gated Mexican shops. The timing is good on the demand side, with contactless and card use rising quickly, but tiendita sales are falling and free instant transfers cap the price of acceptance. The main risk to the market thesis is that payments alone cannot reach the USD 50M a 10x return needs, because that would be 64% of the SAM. The investment case depends on Adelanto and Monedari Plus multiplying revenue per shop, or on moving beyond grocery shops and these two countries. That deserves a conviction discussion at IC.

## Reality test against the return check

| Item | Figure | Source |
|---|---|---|
| Entry ownership | USD 500K / USD 12M cap = 4.17% | Deck slide 15, call notes |
| Required exit value | USD 5M / (4.17% x 0.60) = USD 200M | fund-thesis return check |
| Required revenue at exit | USD 200M / 4x = USD 50M (exit multiple is a PLACEHOLDER, not yet researched) | fund-thesis return check |
| Required growth | USD 50M / USD 1.2M = 42x (stretch band) | Pre-screen |
| USD 50M as a share of SAM at USD 93 per shop | 64% | This analysis |
| USD 50M as a share of SAM at USD 179 per shop | 33% | This analysis |
| Base SOM and bull SOM | USD 3.92M and USD 6.27M (USD 7.54M and USD 12.06M at USD 179) | This analysis |

**FLAG: the market as sized cannot carry the return.** Even with the plan's USD 179 per shop combined with five years of 12% growth (which partly counts the same effect twice), USD 50M would be about 19% of the SAM, more than twice the bull share. The deck's own 2029 plan of USD 21M is also well short of USD 50M. To get there, the company needs one or more of the following: (1) much higher revenue per shop from lending and supplier ordering, (2) a wider target, meaning other micro-merchants, more countries, or the roughly 550,000 shops the census does not count if the deck's 1.2 million holds up, or (3) a higher exit multiple than 4x. This needs a conviction discussion. It is not an automatic reject.

## Open market questions

| # | Question | Why it matters | State |
|---|---|---|---|
| 1 | What is the split of revenue per shop between card take, Monedari Plus and Adelanto (the USD 12K a month residual), and what evidence supports growth toward USD 179 and beyond? | The return check depends on revenue per shop multiplying | OPEN |
| 2 | When will a Colombian card acquirer be signed, and what are Colombian card economics (pricing, interchange, take)? | Half the SAM (USD 40.1M) is contingent on it | OPEN |
| 3 | How is the deck's "1.2 million neighborhood shops in Mexico" defined, compared with the census's 653,000 fixed-premise grocery shops? | Moves the Mexican TAM by up to 84% | OPEN |
| 4 | What share of current merchants are not grocery shops (stationers, greengrocers, tortillerías, pharmacies)? | Would support a wider TAM than grocery shops | OPEN |
| 5 | What do the deck's "5 million shops" and "USD 12B market" mean, and where do they come from? | Unsourced headline claims | OPEN |
| 6 | Is volume moving from card to free QR (38% of volume today), and how does that affect revenue per unit of volume? | Free rails (SPEI, CoDi, DiMo, Bre-B) cap the price | OPEN |
| 7 | Are card volumes per merchant holding up by cohort through the 2025 to 2026 slump in tiendita sales? | Revenue per shop rests on per-merchant volume | OPEN |
| 8 | What share of onboarding attempts fail for lack of a bank account, and could Monedari offer its own payout account? | Tests the 63% gate and a possible way to widen it | OPEN |

## Evolution log

| Date | Version | Change |
|---|---|---|
| 2026-09-29 | Pre-IC, initial | Created from the deck, the first call (2026-09-22), the pre-screen (2026-09-24) and web research. Eight open market questions recorded |

## Sources

Company material (claims until confirmed):
- Monedari seed deck, September 2026 (`_inbox/deck/monedari-seed-deck-2026-09.md`), slides 3 to 10, 14, 15
- First-call notes, 2026-09-22 (`_inbox/pre-ic-calls/2026-09-22-first-call-ceo-cto.md`)
- Pre-screen, 2026-09-24 (`0-prescreen/2026-09-24-monedari-pre-screen.md`)

Web sources:
- [INEGI, Censos Económicos 2024, Reporte de resultados 22/25 (July 2025)](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2025/ce/CE2024_def_RR.pdf)
- [INEGI, ENIF 2024, Comunicado de prensa 49/25 (March 2025)](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2025/enif/ENIF2024_CP.pdf)
- [Milenio, tienditas and card acceptance, citing ANPEC and ENIF 2024](https://amp.milenio.com/negocios/por-que-las-personas-prefieren-pagar-en-efectivo-y-no-con-tarjeta)
- [Emprendedor, tiendita history, citing ANPEC shop count](https://emprendedor.com/tiendita-emprendimiento-historia-mexico-comercio-tradicional/)
- [Publimetro, ANPEC on sales decline and shops at risk (October 2025)](https://www.publimetro.com.mx/noticias/2025/10/17/ieps-ahoga-al-comercio-formal-caen-ventas-15-por-ciento-y-60-mil-tienditas-estan-en-peligro/)
- [DPL News, CNBV Panorama Anual de Inclusión Financiera 2025, terminals at end 2024](https://dplnews.com/?p=300279)
- [DPL News, Mercado Pago passes 1 million terminals in Mexico](https://dplnews.com/?p=287818)
- [Expansión, contactless at 30% and tap-to-phone (June 2026)](https://expansion.mx/economia/2026/06/16/pagos-contactless-alcanzan-30-y-presionan-a-reducir-terminales-en-mexico)
- [Tiendanube, Mexican terminal fee comparison](https://www.tiendanube.com/blog/mx/cual-es-la-mejor-terminal-punto-de-venta-mexico/)
- [Mercado Pago, Point terminal fees](https://www.mercadopago.com.mx/herramientas-para-vender/lectores-point?matt_tool=85113909)
- [Semana, Fenalco on neighborhood shops (450,000)](https://www.semana.com/economia/articulo/fenalco-expone-preocupante-panorama-sobre-ventas-en-las-tiendas-de-barrio/202447/)
- [La República, Fenalco on neighborhood shops (500,000, 40% of commerce)](https://www.larepublica.co/empresas/las-tiendas-de-barrio-son-motor-del-comercio-y-generan-mas-de-575-000-empleos-4212334)
- [La República, Fenalco: 82% of shops saw sales fall or stay flat, second half of 2024](https://www.larepublica.co/empresas/segun-fenalco-82-de-las-tiendas-aseguro-que-sus-ventas-cayeron-al-cierre-de-2024-4072546)
- [Superintendencia Financiera de Colombia, Reporte de Inclusión Financiera 2024](https://www.superfinanciera.gov.co/publicaciones/10115642/para-2024-el-963-de-los-colombianos-adultos-tenia-al-menos-un-producto-de-deposito-o-credito/)
- [BBVA Research, Bre-B column (July 2025)](https://www.bbvaresearch.com/wp-content/uploads/2025/07/20250708-Columna-Bre-B_DQ.pdf)

---
Example Ventures | Private and confidential | 2026-09-29
