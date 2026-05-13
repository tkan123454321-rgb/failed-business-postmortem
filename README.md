# # A Root-Cause Analysis of a Failed Physical Product Through a Systems Lens: How Hitting Bottlenecks Shaped My 3-Question Engineering Framework

### A quick message before we begin

Welcome. This post is more than just a project review; it is the story of how a failed business venture taught me the hard lessons that completely redefined my career path. 

Here, I will sit down and thoroughly dissect that failure. We will explore the root causes and physical bottlenecks through a systems engineering lens, and extract the core, pragmatic lessons I learned along the way.

**To recruiters and future colleagues:** 
I hope this report gives you a transparent look into my mindset, how I analyze problems, and how I learn from mistakes. I believe understanding how we think is the best foundation for working effectively together in the future.

**To everyone else:** 
I have been there. I hope the failures and lessons shared here can offer you some clarity, or at least a new perspective on how to approach a problem. I wish you nothing but the best on your journey.

Now, let's begin the story.

---

## I. The origin story: building a business in a glass jar

Back in early 2024, during my freshman year of university, I founded a small business selling **Terrariums**. 

If you haven't heard of terrariums, simply picture a miniature, living forest enclosed in a glass jar. We used real moss, tiny plants, and soil to build a beautiful, self-contained ecosystem. 

Starting from scratch, I spent nights figuring out how to source raw materials directly and cheaply from China via 1688. I manually crafted the first few test products and connected with veterans in the industry who kindly taught me the "secret sauce" of keeping these tiny ecosystems alive.

I didn't run this entirely alone. Along the journey, I collaborated with a few great friends. We managed to build a mini-business: we planned marketing campaigns, promoted our products, and packed boxes for shipping. 

From June to November 2024, things actually went pretty smoothly. We sold a decent number of terrariums. We weren't making massive profits, but we successfully broke even and covered our initial losses. 

*(Feel free to take a look at my old business page here: **[click here](https://www.facebook.com/cayrium?locale=vi_VN)**.)*

But I realized that this physical system was suffering from **two fatal, unfixable bottlenecks**. These weren't small bugs we could just...fix, they were fundamental architectural flaws in the business pipeline itself. 

That realization forced me to make a tough decision: I stopped totally, shut down the entire business in December 2024, and pivoted my life in a completely different direction. 

## II. The Architecture & The Bottlenecks: Why Physical Pipelines Break

<img width="1410" height="894" alt="Screenshot 2026-05-13 at 21 20 30" src="https://github.com/user-attachments/assets/5654e845-c511-489e-8eaa-335c4099cd4e" />

Before we talk about why it failed, let's look at how this business operated on a daily basis:
*   **Making the Product:** 
    It all started with our Cash pool. We took money out (`Cashflow out`) to buy raw materials like glass jars, moss, and soil. Then, through manual works — me sitting for hours crafting each jar by hand, we turned those materials into finished terrarium jars. 

*   **Finding Customers (Marketing):**
    At the same time, we poured cash and effort into the Marketing engine. We took photos, wrote content, and ran campaigns across Instagram, Facebook, and Threads. 

*   **Shipping (Logistics):**
    Once a product was finished and a customer placed an order, we used motorbikes for local orders, and third-party delivery services for long-distance orders.

*   **The Cashflow Loop:**
    If everything went perfectly, the customer received their terrarium safely, and the money they paid (`Cashflow in`) circled right back into our Cash pool. This allowed us to buy more materials, run more ads, and keep the whole system running.

On paper, it looked like a perfect, sustainable loop. But in reality, physical businesses don't run on paper.
When I deeply analyzed this operations, I found two fatal bottlenecks that made scaling impossible:

### Bottleneck #1: the inability to automate or scale 
The first bottleneck that completely choked our pipeline was the production process itself. 

Unlike a piece of software, which you build once and distribute to millions of users simultaneously or a car, which can be mass-produced using automated assembly lines, crafting a terrarium is 100% manual works. 

but it could have been scaled up by hiring more people. However, terrariums are a niche craft. It is difficult to find employees with the required patience, passion to sit down and make these products. 

This is exactly like an data infrastructure unable to adapt or scale up when massive, high-volume data streams flow in.*

### Bottleneck #2: The logistics limit
The second bottleneck was the inability to distribute the product to customers in other areas. 

Because the internal layout of a terrarium (the layers of soil, moss, and tiny plants) is highly complex, normal long-distance shipping was out of the question. We were restricted to either safely self-delivering within our local area, or hiring specialized expensive—logistics services, which would slowly drain the business's revenue pool. 

This is like building a data architecture that is physically constrained to only absorb a very specific data source, completely unable to expand its reach to broader data sources.*

## III. The root cause: A flawed blueprint from day one

When a system has two fatal, unfixable bottlenecks, the problem isn't just operational. If we dig down to the absolute root cause, this business failed because of one thing: the product choice itself.

Choosing the wrong product from the very beginning is exactly like drawing a fundamentally flawed data architecture on day one. It doesn't matter how many shiny features you build on top of it, how many features you apply, or how beautifully you design it. If the core foundation is wrong, it cannot be fixed. The system will eventually fail.

Instead of zooming out to evaluate this broken blueprint, I fell into a classic builder's trap: I got completely lost in the details.

I was deeply obsessed with the micro-level tasks—researching how to perfectly care for the plants, designing new terrarium layouts, and brainstorming unique concepts for product photos. I even sat down and watched a 10-hour tutorial on how to professionally edit videos on Adobe Premiere:)) (editing videos can be done easily with Capcut) 

I spent all my energy "over-engineering" the marketing and the aesthetics, completely forgetting to step back and look at the original architectural blueprint. I was polishing the windows of a house that was built on an unscalable foundation.

## IV. The unanswered question & the decision framework

Why did I choose the wrong product from day one? 

To be completely honest, even a year after shutting down the business, I still don't have a perfect answer. The simple truth is: I lacked experience. I just didn't foresee all the possibilities, edge cases, and risks that could happen in reality.

But I realized something important: As I continue to stumble and learn in my career, I will gradually build a mental checklist - a set of strict questions to ask myself before making any major decision or starting a new project. The more I experience, the thicker this checklist will become, helping me minimize risks right from the starting line.

From the ruins of that failed business, I have my very first set of guiding principles. Now, before I commit to building anything, I force myself to ask:

### Question 1: Does it actually solve a real problem for the "Customers"?

In my mindset now, "everything is a product". And a product exists solely to solve a specific problem for a specific group of customers. 

The "customers" aren't just someone paying for a product/service. Your customer could be your boss, your teammates, or even the recruiter reading this exact post. 
*(Acutally, my technical skills and mindset are my "product". This article is a product designed to help recruiters understand how I think, thereby solving their problem of making a faster, better hiring decision).*

Back then, I chose to sell terrariums simply because I thought they solved a basic problem: decorating a boring desk. 

Today, I apply this exact same filter to my work. Whether I am asked to develop a new feature, build a data architecture, or design a new dashboard, the very first question that pops into my head is: *"Does this actually solve a real problem for my customers? If not, I don't build it."*

### Question 2: If it solves the problem, is it the simplest, most cost-effective, and optimal way to do it?

This is my foundational rule to avoid the trap of Over-engineering — a trap I fell deeply into during my business days.

Back then, I faced a basic problem: *How do I make my products look attractive on social media?* 
The simplest, most cost-effective solution would have been to use a regular phone and edit with free, intuitive apps like CapCut or Lightroom. 

What did I do instead? I went out and bought an iPhone 15 Pro just so I could shoot in Apple ProRAW format. Then, I spent a whole weekend watching a 10-hour tutorial by some random guy on the internet just to learn how to color-grade on Adobe Premiere. 

Did it solve the problem? Yes. Was it the optimal and most resource-efficient way? Absolutely not. I wasted massive amounts of time and capital on a tool that was way too complex for the problem at hand. Today, whenever I design a feature, I always ask this question to ensure I am using the right tool for the job.

### Question 3: Is this solution scalable, adaptable, and stable for the future?

This is the most important lesson I learned from the two fatal bottlenecks of that physical business. If a system cannot adapt to high volume or handle unexpected errors, it will eventually break.

I strictly applied this exact question to my current data project: the **[[Quantamental Screener for Vietnam Stocks](https://github.com/tkan123454321-rgb/VN_stocks_quantamental_screener)]**. 

When building the data pipeline for this screener, I could have chosen the easy route: just write the scraping scripts, run them, and ignore system monitoring. However, remembering my past failures, I knew I had to build for future stability. 

That is why I decided to set up a complete Observability stack using Vector, Loki, and Grafana to track logs and monitor the entire system's health. I knew that as the data volume scaled up and inevitable errors occurred, without a proper tracking architecture, debugging would be really frustrating. I will not  be able to identify those bottlenecks quickly. By answering Question 3, I ensured my data infrastructure wouldn't hit a hard ceiling like my terrarium business did.

