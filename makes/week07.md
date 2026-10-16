# DH 101 - Week 7 Make: Build a Digital Map of AI's Infrastructures

**Student:** Anh Tu Le  
**Interactive map:** [AI Digital Map - The Hidden Geographies of AI Infrastructure](https://www.google.com/maps/d/u/0/view?mid=1v4k-2_PIpNq3_-zrMgrvt-43CkSHezA&usp=sharing)  
**Week 7 website:** [https://tyler-anh.github.io/DH101/makes/week07](https://tyler-anh.github.io/DH101/makes/week07)

---
## 1. Research Documentation

This map treats AI as a material system rather than a product that exists only in software. I selected three layers: corporate decision centers and legal addresses, data centers, and mineral extraction or processing sites. Together, they show that decisions, computing capacity, and raw materials are spread across different places. The map asks how that separation distributes power, environmental pressures, and visibility, rather than treating the pins as a complete supply chain.

I documented 20 location records using company filings, official facility pages, a government facility registry, geological records, and research on infrastructure and labor. The inventory contains six corporate or legal addresses, seven data-center sites, and seven mineral sites. I label the OpenAI point as a registered controller address because the cited privacy policy does not prove it is a headquarters. Several data-center and mining pins are city- or region-level approximations; the Microsoft West Des Moines pin has a more precise address and coordinates in the Iowa Department of Natural Resources record.

The sources also help explain why infrastructure gathers in particular regions. Virginia's legislative research office identifies strong fiber connectivity, reliable energy, available land, proximity to major customers, and tax incentives as factors behind Northern Virginia's data-center concentration (Virginia JLARC, 2024). Google describes The Dalles as having a skilled local workforce, a business-friendly environment, and enhanced energy infrastructure (Google Data Centers, n.d.). Iowa publishes eligibility-based tax incentives for qualifying data centers (Iowa Department of Revenue, 2025), although that policy alone does not prove that any individual facility received a benefit. These examples make location a political and economic decision, not just a technical one.

The hardest information to find was evidence linking one mine to a particular AI company or model. Public sources identify facilities and deposits more easily than they disclose supplier relationships, actual site-level energy and water use, community disputes, tax arrangements, or who receives long-term benefits. Company pages communicate operators' own accounts; public records are better for some location details but often say little about people's experiences. Labor is also easy to leave off a map: TIME's reporting on Kenyan data-labeling workers (Perrigo, 2023) and the ILO's discussion of invisible labor in the cobalt sector (ILO, 2024) show that AI depends on human work as well as land and electricity. These sources do not represent every worker or establish conditions at every mapped mine. What surprised me most is how much can be located precisely while responsibility and lived impacts remain difficult to trace. Those missing details are part of the map's argument, not gaps to fill with guesses.


### Location inventory and source notes

The inventory below documents 20 distinct location records across three layers. Each description separates what the source confirms from a broader interpretation of why that location matters.


#### Corporate decision centers and legal addresses

- **OpenAI - San Francisco, California.** The cited US privacy policy lists 1455 Third Street as OpenAI OpCo, LLC's registered controller address. Label this point as a registered business/legal address, not as proof of a server location or independently verified headquarters. [Source: OpenAI US Privacy Policy](https://openai.com/policies/privacy-policy/)
- **Alphabet / Google - Mountain View, California.** Alphabet's 2025 Form 10-K lists 1600 Amphitheatre Parkway as its principal executive office. This is a decision-making node; Google's compute infrastructure is distributed well beyond it. [Source: Alphabet 2025 Form 10-K (SEC)](https://www.sec.gov/Archives/edgar/data/1652044/000165204426000018/goog-20251231.htm)
- **Microsoft - Redmond, Washington.** Microsoft's 2026 Form 10-K lists One Microsoft Way, Redmond, as its business address. Keep this office distinct from its data-center campuses, including the Iowa facility in the next layer. [Source: Microsoft 2026 Form 10-K (SEC)](https://www.sec.gov/Archives/edgar/data/789019/000119312526323660/msft-20260630.htm)
- **Meta Platforms - Menlo Park, California.** Meta's 2025 Form 10-K lists 1 Meta Way, Menlo Park, as its principal executive office. The location represents corporate governance and strategy, not the physical footprint of its data-center network. [Source: Meta Platforms 2025 Form 10-K (SEC)](https://www.sec.gov/Archives/edgar/data/1326801/000162828026003942/meta-20251231.htm)
- **NVIDIA - Santa Clara, California.** NVIDIA lists its corporate location at 2788 San Tomas Expressway, Santa Clara. This is useful for mapping a major hardware company, but the address alone does not identify where its chips are fabricated or assembled. [Source: NVIDIA official locations page](https://www.nvidia.com/en-us/contact/)
- **Amazon - Seattle, Washington.** Amazon's 2025 Form 10-K lists 410 Terry Avenue North, Seattle, as its principal executive office. AWS computing infrastructure is geographically distributed, so the office should not be treated as the location of all Amazon computing. [Source: Amazon 2025 Form 10-K (SEC)](https://www.sec.gov/Archives/edgar/data/1018724/000101872426000004/amzn-20251231.htm)

#### Computing infrastructure and data centers

- **QTS Ashburn 1 - Sterling, Virginia.** QTS identifies a two-building data-center campus at 22271 Broderick Drive and 22280 Randolph Drive, Sterling, Virginia. Virginia's JLARC review attributes Northern Virginia's concentration partly to fiber connectivity, reliable energy, available land, customer proximity, and tax incentives. That explains regional appeal, not the energy or water impact of this particular campus; as a colocation site, it should not be assigned one AI customer without evidence. [Source: QTS Ashburn 1 campus](https://q.com/data-centers/ashburn-1/)
- **Microsoft - West Des Moines, Iowa.** The Iowa DNR registry identifies a Microsoft Data Center at 3590 S 8th Street, West Des Moines, with coordinates 41.51813, -93.71216. This is one of the more precise pins because a public government facility record provides a mapped point. Iowa also publishes tax incentives for qualifying data-center investments, but the policy alone does not show whether this site claimed a particular benefit. [Source: Iowa DNR Facility Explorer](https://facilityexplorer.iowadnr.gov/FacilityExplorer/SiteDetail.aspx?facID=312438814)
- **Google - The Dalles, Oregon.** Google identifies The Dalles as one of its data-center locations and describes local water-stewardship efforts. Its own site page lists a skilled local workforce, a business-friendly environment, and enhanced energy infrastructure among the reasons for choosing the area. This is the operator's explanation, not an independent audit of water use or local effects. [Source: Google data centers: Oregon](https://www.datacenters.google/locations/oregon/)
- **Google - Council Bluffs, Iowa.** Google states that it began operating a data center in Council Bluffs in 2007 and describes later investment and watershed work. Comparing this pin with nearby Iowa facilities shows how computing infrastructure can cluster regionally. State tax incentives are part of the broader policy context, but I do not assume this specific facility received a benefit without site-specific evidence. [Source: Google data centers: Iowa](https://www.datacenters.google/locations/iowa/)
- **Meta - Los Lunas, New Mexico.** Meta lists Los Lunas as a data-center location with a multibillion-dollar investment figure and construction/employment context. Treat these as company-reported claims, not a full accounting of water, energy, or community costs. [Source: Meta US data-center locations](https://datacenters.atmeta.com/us-locations/)
- **Meta - Forest City, North Carolina.** Meta lists Forest City as an established data-center location. Its presence broadens the map beyond western and Midwestern clusters and helps show the national spread of facilities. [Source: Meta US data-center locations](https://datacenters.atmeta.com/us-locations/)
- **Meta - Prineville, Oregon.** Meta lists Prineville among its Oregon data-center locations. Compare this site with Google's The Dalles location to show that several companies depend on infrastructure sited in the same broader region, without claiming a direct connection between their facilities. [Source: Meta US data-center locations](https://datacenters.atmeta.com/us-locations/)

#### Mineral extraction and processing

- **MP Materials - Mountain Pass Mine, California.** MP Materials identifies Mountain Pass as a rare-earth mining and materials site. It represents an upstream material node in hardware supply chains; available public evidence here does not establish that output from this mine goes into a named AI model or specific data center. [Source: MP Materials: Mountain Pass](https://www.mpmaterials.com/mountain-pass)
- **Albemarle - Silver Peak, Nevada.** Albemarle describes Silver Peak as a lithium brine operation in Nevada. The point makes extraction visible alongside corporate and compute locations, while leaving any particular end-customer relationship unclaimed. [Source: Albemarle: Silver Peak](https://www.albemarle.com/us/en/silver-peak)
- **Tenke Fungurume - Lualaba Province, Democratic Republic of the Congo.** The mining company describes its operations as a major copper and cobalt producer, with mines and a processing plant in the Fungurume/Kolwezi area. Copper and cobalt matter to broad electrical and technology supply chains, but this map does not prove a direct route to a particular AI company. For wider context, the ILO has discussed concerns about the often-invisible labor behind the cobalt sector; that sector-level source is not a finding about conditions at this specific operator. [Source: Tenke Fungurume Mining official site](https://tfmofficial.com/)
- **SQM - Salar de Atacama, northern Chile.** SQM lists the Salar de Atacama among its northern Chilean operations and describes brine concentration and mineral production there. Pin the site as a mineral-production location and avoid presenting the entire operation as dedicated to AI. [Source: SQM: Operations in Chile](https://sqm.com/en/acerca-de-sqm/informacion-corporativa/nuestras-faenas/)
- **SQM - Salar del Carmen, Antofagasta, Chile.** SQM identifies Salar del Carmen as a plant producing lithium carbonate and lithium hydroxide. This is a processing site rather than the same kind of point as a brine deposit, so the map layer should include both extraction and processing in its name. [Source: SQM: Operations in Chile](https://sqm.com/en/acerca-de-sqm/informacion-corporativa/nuestras-faenas/)
- **Fenix / Salar del Hombre Muerto - Catamarca, Argentina.** Argentina's SEGEMAR mineral-deposit database places Salar del Hombre Muerto/Fénix in Catamarca and records lithium and borates. Its status is recorded as in development, which is an important distinction from a fully operating mine. [Source: SEGEMAR mineral deposit record](https://sigam.segemar.gov.ar/segedoc/res/img/sigam_yacimientos/dp11290.html)
- **Bayan Obo - Inner Mongolia, China.** A US Geological Survey publication documents Bayan Obo as a major rare-earth, iron, and niobium deposit in Inner Mongolia. It anchors the map's mineral layer in China, but it does not prove that its output supplies any one company in the corporate layer. [Source: USGS Bayan Obo deposit study](https://pubs.usgs.gov/bul/b2143/intro.html)

---
## 2. Artist Statement

My map argues that AI's geography is split between corporate decision-making, computing sites, and places that provide materials for wider electronics and power systems. These layers do not prove a mine-to-model supply chain. Their separation raises a question: who controls AI, and who provides the land, energy, minerals, and labor that make it possible?

The pins also show unequal visibility. Corporate addresses are relatively easy to document, while a location marker cannot show a data center's water use or energy demand, working conditions at mines, or whether nearby communities share in the benefits. Reporting on Kenyan content moderators and cobalt-sector labor reminds me that AI's apparent automation still depends on people whose work is less visible than the products.

This is where Data Feminism matters. A map is not neutral: choosing locations and sources shapes what viewers see. A technology executive might emphasize investment and jobs; a resident might ask about utility costs and water; a mine worker might prioritize wages and safety. My sources document facilities better than those perspectives, so this map cannot speak for everyone affected. It is a small counter-map to a corporate story of seamless AI, putting infrastructure, extraction, and less-visible labor back into view.

I leave direct supplier lines out unless evidence supports them. That choice makes the map less tidy, but more honest. Its missing data shows how difficult it can be to trace responsibility from the places that benefit from AI to the places that bear its costs.


### Map design and annotation choices

For a clear visual hierarchy, use one color/icon system per layer and keep labels short. The interactive map should remain legible at a world view while allowing a viewer to toggle layers and open a pin for its evidence and caveat.

- **Layer 1 - Corporate decision centers / legal addresses:** Blue circles or office icons. Use a consistent label style. Clearly tag the OpenAI point as a registered controller address rather than a verified headquarters.
- **Layer 2 - Computing infrastructure:** Purple squares or server icons. Use site name plus operator as the label. Add a concise note about the documented location rationale, local resource questions, and any source limitation.
- **Layer 3 - Mineral extraction and processing:** Ochre mine/mineral icons. Use separate wording for mines, brine operations, deposits, and processing plants. Note the human labor involved in extraction, but do not present general sector reporting as evidence about one named operator.
- **Pin annotation pattern:** For every pin: (1) what the location is; (2) what the source confirms; (3) why it matters to the wider AI infrastructure question; and (4) one limit or missing fact. Include a source link inside the pin description.
- **Connections and visual restraint:** Use the full-world extent, a short title/subtitle, a visible legend, and layer toggles. Do not draw route lines from a mine to a named company or data center unless a source documents that supply relationship. Address content moderation and data-labeling work in contextual annotations and the statement, while keeping the map to the three selected layers.

---
## 3. Attribution and Sources

**Mapping platform:** Google My Maps; map link above.


### Theoretical and critical framework

- Crawford, Kate. Atlas of AI: Power, Politics, and the Planetary Costs of Artificial Intelligence. Yale University Press, 2021.. [https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/](https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/)
- D'Ignazio, Catherine, and Lauren F. Klein. Data Feminism. MIT Press, 2020.. [https://mitpress.mit.edu/9780262044004/data-feminism/](https://mitpress.mit.edu/9780262044004/data-feminism/)
- Greenpeace International. Clicking Clean, 2017. Used as historical background on digital infrastructure and energy; not treated as a current facility-level energy audit.. [https://www.greenpeace.org/international/publication/6826/clicking-clean-2017/](https://www.greenpeace.org/international/publication/6826/clicking-clean-2017/)
- Perrigo, Billy. “Exclusive: OpenAI Used Kenyan Workers on Less Than $2 Per Hour to Make ChatGPT Less Toxic.” TIME, 2023.. [https://time.com/6247678/openai-chatgpt-kenya-workers/](https://time.com/6247678/openai-chatgpt-kenya-workers/)
- International Labour Organization. “Addressing the invisible labour behind the cobalt mining industry.” 2024.. [https://www.ilo.org/resource/news/addressing-invisible-labour-behind-cobalt-mining-industry](https://www.ilo.org/resource/news/addressing-invisible-labour-behind-cobalt-mining-industry)

### Corporate addresses

- OpenAI - US Privacy Policy; registered controller address. [https://openai.com/policies/privacy-policy/](https://openai.com/policies/privacy-policy/)
- Alphabet / Google - 2025 Form 10-K, SEC. [https://www.sec.gov/Archives/edgar/data/1652044/000165204426000018/goog-20251231.htm](https://www.sec.gov/Archives/edgar/data/1652044/000165204426000018/goog-20251231.htm)
- Microsoft - 2026 Form 10-K, SEC. [https://www.sec.gov/Archives/edgar/data/789019/000119312526323660/msft-20260630.htm](https://www.sec.gov/Archives/edgar/data/789019/000119312526323660/msft-20260630.htm)
- Meta Platforms - 2025 Form 10-K, SEC. [https://www.sec.gov/Archives/edgar/data/1326801/000162828026003942/meta-20251231.htm](https://www.sec.gov/Archives/edgar/data/1326801/000162828026003942/meta-20251231.htm)
- NVIDIA - official locations. [https://www.nvidia.com/en-us/contact/](https://www.nvidia.com/en-us/contact/)
- Amazon - 2025 Form 10-K, SEC. [https://www.sec.gov/Archives/edgar/data/1018724/000101872426000004/amzn-20251231.htm](https://www.sec.gov/Archives/edgar/data/1018724/000101872426000004/amzn-20251231.htm)

### Data-center and public facility records

- QTS - Ashburn 1 campus. [https://q.com/data-centers/ashburn-1/](https://q.com/data-centers/ashburn-1/)
- Virginia Joint Legislative Audit and Review Commission - Data Centers in Virginia (regional location factors and impacts). [https://jlarc.virginia.gov/landing-2024-data-centers-in-virginia.asp](https://jlarc.virginia.gov/landing-2024-data-centers-in-virginia.asp)
- Iowa Department of Revenue - Data Center Sales and Use Tax Incentives. [https://revenue.iowa.gov/taxes/tax-guidance/sales-use-excise-tax/data-centers](https://revenue.iowa.gov/taxes/tax-guidance/sales-use-excise-tax/data-centers)
- Meta - US data-center locations. [https://datacenters.atmeta.com/us-locations/](https://datacenters.atmeta.com/us-locations/)
- Iowa Department of Natural Resources - Microsoft Data Center facility record. [https://facilityexplorer.iowadnr.gov/FacilityExplorer/SiteDetail.aspx?facID=312438814](https://facilityexplorer.iowadnr.gov/FacilityExplorer/SiteDetail.aspx?facID=312438814)
- Google - The Dalles, Oregon data center. [https://www.datacenters.google/locations/oregon/](https://www.datacenters.google/locations/oregon/)
- Google - Iowa data centers. [https://www.datacenters.google/locations/iowa/](https://www.datacenters.google/locations/iowa/)

### Mineral extraction and processing

- MP Materials - Mountain Pass Mine. [https://www.mpmaterials.com/mountain-pass](https://www.mpmaterials.com/mountain-pass)
- Albemarle - Silver Peak. [https://www.albemarle.com/us/en/silver-peak](https://www.albemarle.com/us/en/silver-peak)
- Tenke Fungurume Mining - official site. [https://tfmofficial.com/](https://tfmofficial.com/)
- SQM - Operations in Chile. [https://sqm.com/en/acerca-de-sqm/informacion-corporativa/nuestras-faenas/](https://sqm.com/en/acerca-de-sqm/informacion-corporativa/nuestras-faenas/)
- SEGEMAR - Salar del Hombre Muerto / Fénix deposit record. [https://sigam.segemar.gov.ar/segedoc/res/img/sigam_yacimientos/dp11290.html](https://sigam.segemar.gov.ar/segedoc/res/img/sigam_yacimientos/dp11290.html)
- US Geological Survey - Bayan Obo deposit study. [https://pubs.usgs.gov/bul/b2143/intro.html](https://pubs.usgs.gov/bul/b2143/intro.html)

**AI assistance disclosure:** ChatGPT assisted with organizing and expanding the source-linked location inventory, checking source claims against the cited pages, and revising the research documentation and artist statement. The author remains responsible for reviewing the current Google My Maps pins, confirming each source, applying the layer design, and checking that the live map matches this inventory.
