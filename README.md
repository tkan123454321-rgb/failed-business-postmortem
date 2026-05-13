# A root-cause analysis of a failed physical product through a systems lens: How hitting physical bottlenecks led to the revelation of the "5-Circle Ikigai" philosophy that redefined my path

### A quick message before we begin

Welcome. This post is more than just a project review; it is the story of how a failed business venture taught me the hard lessons that completely redefined my career path. 

Here, I will sit down and thoroughly dissect that failure. We will explore the root causes and physical bottlenecks through a systems engineering lens, and extract the core, pragmatic lessons I learned along the way.

**To recruiters and future colleagues:** 
I hope this report gives you a transparent look into my mindset, how I analyze problems, and how I learn from mistakes. I believe understanding how we think is the best foundation for working effectively together in the future.

**To everyone else (especially if you are feeling lost in your career choices):** 
I have been there. I hope the frameworks and lessons shared here can offer you some clarity, or at least a new perspective on how to choose your path. I wish you nothing but the best on your journey.

Now, let's begin the story.

---

## I. The origin story: building a business in a glass jar

Back in early 2024, during my freshman year of university, I founded a small business selling **Terrariums**. 

If you haven't heard of terrariums, simply picture a miniature, living forest enclosed in a glass jar. We used real moss, tiny plants, and soil to build a beautiful, self-contained ecosystem. 

Starting from scratch, I spent nights figuring out how to source raw materials directly and cheaply from China via 1688. I manually crafted the first few test products and connected with veterans in the industry who kindly taught me the "secret sauce" of keeping these tiny ecosystems alive.

I didn't run this entirely alone. Along the journey, I collaborated with a few great friends. We managed to build a mini-business: we planned marketing campaigns, promoted our products, and packed boxes for shipping. 

From June to November 2024, things actually went pretty smoothly. We sold a decent number of terrariums. We weren't making massive profits, but we successfully broke even and covered our initial losses. 

*(Feel free to take a look at my old business page here: **[click here](https://www.facebook.com/cayrium?locale=vi_VN)**.)*

But I realized that this physical system was suffering from **two fatal, unfixable bottlenecks**. These weren't small bugs we could just...fix — they were fundamental architectural flaws in the business pipeline itself. 

That realization forced me to make a tough decision: I stopped totally, shut down the entire business in December 2024, and pivoted my life in a completely different direction. 

## II. The Architecture & The Bottlenecks: Why Physical Pipelines Break

*(Note: [Insert your Excalidraw System Diagram here])*

If we view this business as a data pipeline, the flow is straightforward: we ingest raw materials, process them into a final product, and deliver the payload to the customer. However, unlike a digital system, this physical pipeline had severe limitations. 

When I deeply analyzed our operations, I found two fatal bottlenecks that made scaling impossible:

### Bottleneck 1: The "Processing" Node (The Manual Labor Limit)
In software engineering, if your server experiences a traffic spike, you can simply auto-scale horizontally by spinning up more instances. In my terrarium business, the "CPU" was my own two hands. 

Crafting a highly detailed, aesthetic terrarium takes hours of intense focus. It is pure manual labor. The maximum output per day is strictly capped by human stamina. To scale this, I would have had to hire and train skilled artisans, which would drastically increase operational costs and introduce massive quality control issues. 

Our production node was a **Single Point of Failure (SPOF)**. The effort-to-output ratio was strictly linear — there was absolutely no leverage.

### Bottleneck 2: "Packet Loss" & Strict "Runtime Environments"
Even if we magically solved the processing bottleneck, the delivery and maintenance phases were logistical nightmares.

*   **High "Packet Loss" in Logistics:** We were shipping fragile glass jars filled with soil and delicate plants across provinces. No matter how well we packed them with bubble wrap, the third-party logistics network was out of our control. Jars broke. Soil flipped. In networking terms, our "packet loss" rate was unacceptably high, leading to dead stock and expensive refunds.
*   **Strict "Runtime" Dependencies:** A terrarium is a living ecosystem. We essentially shipped a product that required a highly specific "runtime environment" to survive. It needs precise LED lighting and watering schedules. If a customer forgot to turn on the light (bad environment setup), the system crashed (the plants died). We couldn't control the end-user's environment, but we still took the blame and the financial hit when things failed.

These physical constraints meant that no matter how hard we worked or how much money we pumped into marketing, the system was inherently unscalable. I realized that a business bound by physical limitations is a business with a hard ceiling.
