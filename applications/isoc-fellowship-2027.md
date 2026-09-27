# Internet Society Fellowship 2027: plan and draft

- **Status:** open now
- **Step 1, you:** enrol in the Pre-Fellowship Training at internetsociety.org/fellowship and finish every module by **22 Nov 2026**. It's self-paced over about 2.5 months, so start this week.
- **Step 2:** within 24 hours of finishing, ISOC emails you the application link. The application closes **18 Dec 2026**.
- **What you get:** a 10-month fellowship, a project stipend of up to USD 5,000, and travel support to one global or regional Internet event (e.g. IGF). Whether airfare is covered in full isn't stated, so confirm in the FAQ before relying on it.
- **Fee:** none
- **Needed:** the application form, plus a video of up to 3 minutes about your project idea, your progress and your milestones

## Suggested track: Internet Connectivity

The project must be something **you** are willing to deliver over 10 months. The draft below is only a proposal built from your real experience (Wi-Fi-based location inference at KHI, geospatial and smart-city interests, living in Japan as a foreign resident). Change or replace it before you use it.

### Project title
Shelter Connect Map: open data on emergency Wi-Fi at evacuation shelters in Tokyo, for residents who don't read Japanese

### Problem (~120 words)
When a disaster hits, Japan opens free emergency Wi-Fi (the `00000JAPAN` network) and designates evacuation shelters. Information about which shelters actually have usable connectivity is scattered across ward websites, mostly in Japanese, and rarely checked in the field. Tokyo has hundreds of thousands of foreign residents. For many of them, a phone connection is their only access to alerts, family and translation tools. If you can't find a connected shelter in a language you read, the connectivity doesn't really exist for you.

### What I will build (~130 words)
- A small open dataset, pilot-scoped to **one Tokyo ward**, of designated shelters with published connectivity details. I'll collect field measurements (signal strength, throughput, whether a public Wi-Fi network is present) from a simple phone-based survey tool I write myself.
- A lightweight map in English, Japanese and Hindi. It needs no login and loads on a poor connection.
- A short, repeatable method so volunteers or other wards can extend the data.

I have built this kind of pipeline professionally: I developed a system that turns Wi-Fi signal measurements into location estimates, with a Python backend and a React dashboard on Azure.

### Milestones (10 months)
1. Months 1–2: collect public shelter data for the pilot ward and check the licence terms. Talk to the ward's international exchange desk about what would be useful.
2. Months 3–4: build the survey tool and do field measurements at an initial set of shelters.
3. Months 5–6: release the map in three languages and publish the dataset openly.
4. Months 7–8: run usability sessions with foreign residents, then fix what doesn't work.
5. Months 9–10: document the method and present the results at the funded Internet event.

### Budget sketch (≤ USD 5,000)
Hosting and domain (about USD 300), field-survey travel within Tokyo (about USD 400), translation review (about USD 800), usability-session costs (about USD 500), contingency. Refine this after the training.

## 3-minute video script (~330 words, about 2:40 spoken)

> Hi, I'm Poornapragnya. I'm a software engineer from India, and I live and work in Tokyo.
>
> Japan is one of the best-prepared countries in the world for earthquakes. When a big one hits, the government opens free emergency Wi-Fi and wards open evacuation shelters. But information about which shelters really have usable connectivity is scattered across ward websites, mostly in Japanese, and hardly anyone measures it on the ground.
>
> For a foreign resident, that gap matters. In an emergency your phone is how you get alerts, reach family and translate instructions. If you can't find a connected shelter in a language you read, the connectivity may as well not exist.
>
> My project, Shelter Connect Map, starts small: one Tokyo ward. I'll combine the ward's public shelter data with field measurements from a simple phone survey tool I'll write: signal strength, throughput, and whether a public Wi-Fi network is present. Then I'll publish an open dataset and a lightweight map in English, Japanese and Hindi that works on a weak connection.
>
> I've done this kind of work before. In my last role I built a system that turns Wi-Fi signal measurements into location estimates, from the backend to the dashboard to the cloud deployment.
>
> So far I've [UPDATE AFTER TRAINING: e.g., collected the ward's public shelter list and sketched the data model].
>
> My milestones: public data and local conversations in the first two months, field measurements by month four, the multilingual map by month six, testing with foreign residents after that, and a documented method other wards can reuse by the end.
>
> The fellowship would give me the grounding in how connectivity policy works and the community to take this beyond one ward. Thank you.

## Before submitting
- [ ] You approve or replace the project idea
- [ ] Finish the Pre-Fellowship Training by 22 Nov
- [ ] Record the video and fill in the "progress so far" line truthfully
- [ ] You submit by 18 Dec
