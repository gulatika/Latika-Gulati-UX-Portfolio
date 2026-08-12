# Portfolio copy for Claude Design (final)

Paste-ready. Your original site copy is verbatim except one em dash on the Identity Platform page (now a colon) and the Identity Platform reflection, which was accidentally copied from iOTP and is now rewritten. New placeholder sections are clearly labeled.

**Home featured cards:** iOTP and Identity Platform lead as full cards. Project Expedition, Internal Tools, One AP, and Brand & Identity sit in the lighter list. Project Expedition graduates back to a featured card once its case study is written.

---

# HOME

**Hero headline** (placeholder, to be finalized)
Hi, I'm Latika. I design friction on purpose.

**Hero subhead**
I know when to smooth the path and when a little resistance is the point, because I understand what it takes to build. Twelve years across engineering and product design, and 24 patents along the way.

**Case study card summaries**

- Calibrating friction on iOTP for Capital One: Streamlined Capital One's Interactive OTP experience, balancing security requirements with measurable usability gains.
- Designing for Alignment with the Identity Platform at Capital One: Led workshops and influenced cross-functional alignment to lay the foundation for Capital One's Identity Platform.
- Rethinking how travelers find a destination (Project Expedition): Full case study incoming.
- Designing internal tools for developers at Capital One: Consolidated and redesigned three internal tools into a single, unified platform, significantly streamlining and enhancing the developer experience.
- Streamlining AP/AR processes with American Express: Enhanced both American Express' Accounts Payable and Accounts Receivable solutions, driving increased efficiency and value.
- Brand and identity work: A small collection of logos and marks.

**Philosophy block**

I believe that great design calibrates friction.

Users shouldn't have to think about the interface. They should just be able to accomplish what they came to do. But sometimes friction is the feature. Verifying your identity with a bank should feel secure. Navigating a complex help center should feel guided. My job is to know the difference and design accordingly.

My background in software development means I understand technical constraints and can collaborate with engineering teams in their language. This helps me design solutions that are not only right for the user, but feasible to build and actually get shipped.

**Seeking line**
I'm seeking product design opportunities where systems thinking, stakeholder alignment, and technical collaboration matter. Based in the DC area, open to relocating and remote roles.

---

# CASE STUDY 1 — iOTP (flagship, featured)

**Title**
Calibrating Friction: Redesigning iOTP Authentication at Capital One

**Metadata**
Role: Solo UX/UI Designer
Team: Me (designer), Product Owner, Developers
Timeline: 6 weeks
Highlighted Tools: Figma, UserTesting.com

**The Problem: A Secure Flow with a Drop-Off Problem**

Capital One customers are quietly being protected by a layered authentication system every time they log in. For more risky tasks like wiring money, users are asked to complete a secondary authentication step to prove it's really them.

One of the more secure methods in our toolkit was Interactive OTP (iOTP), a verification flow where instead of an auto-filled code, users were asked to leave the app, go to their messages, and actively confirm their identity. While more secure than standard OTP, it introduced more friction.

The issue for the iOTP flow was that users kept dropping off. They wouldn't realize they were in a completely different flow, expected the code to auto-populate, and abandoned it when it didn't. Low completion by users meant low adoption by Capital One lines of business, meaning Capital One was left more exposed to risk.

**Understanding the role of friction in authentication**

Before touching any designs, I dug into the research database to see what relevant information I could find. I learned that users expect a little bit of friction when accessing their money to feel safe. They want to feel that their bank takes protecting their money seriously, but they don't want to slow down unnecessarily either. The goal for Identity services is never to eliminate friction but instead to calibrate it.

**Finding the drop off point**

Through looking at funnel analytics, the core failure point was that users didn't realize they had to leave the Capital One app. Since modern OTP had trained people to expect an autofill of the code, I often heard "huh, that's odd" when the code didn't autofill and the completion rate reflected it.

**Brainstorming Solutions, Testing with Users**

I designed three distinct flows, each exploring a different intervention:

- Adding an explanatory screen before the action
- Introducing a modal to interrupt and redirect attention at the critical moment
- Revising copy to set expectations earlier in the flow

Each flow was tested with 10 users on UserTesting.com and benchmarked against the original iOTP flow as a control (40 users total). I ran 2 rounds of iteration, refining based on what the data showed and technical feasibility rather than what I assumed would be best.

**The Validated Approach**

The winning approach combined three changes:

1. A modal at the critical moment: rather than a preparatory screen users could skim past, a modal interrupted the flow at the exact point where confusion was highest, forcing a moment of pause.
2. Revised copy: language that reframed the extra step as a sign of stronger security rather than an inconvenience. The goal was to make users feel like the friction was working for them, not against them. For users moving quickly through the flow, the copy provided a clear signal that iOTP was different from standard OTP.
3. One text instead of two: a behind-the-scenes optimization that reduced the number of SMS sent per authentication attempt, lowering cost per session without any impact on the user experience. Better UX and lower cost is a win-win!

**Outcomes, handoff, and reflection**

The redesign projected a 20% improvement in user completion rates based on usability testing data, ahead of A/B test launch. SMS cost per session was also reduced, lowering operational overhead without any user-facing changes. These findings were then presented directly to the Capital One Card team, the largest line of business, with the expectation that smaller lines of business would follow suit once Card was on board.

With usability testing complete, designs were handed off to development and queued for A/B testing to validate the projected improvements at scale.

This project reinforced something I carry into every authentication or high-stakes flow: the goal is never zero friction. It's the right friction. Users need to feel that their bank is working to protect them and the design's job is to make that clear.

**Testimonial to feature here** (see testimonials section): Noelle Fair.

---

# CASE STUDY 2 — Identity Platform (featured)

**Title**
Designing for Alignment: The Identity Platform at Capital One

**Metadata**
Role: UX Designer in a cross-functional task force
Team: 20+ stakeholders across design, engineering, product, and identity leadership
Timeline: 6 months
Highlighted Tools: Figma, workshop facilitation, PRD collaboration

**Overview and problem**

Capital One's Identity services are siloed by a single team, which means when a line of business needed to integrate login, authentication, or verification into a new product, they had to come to the Identity team directly. A single PM served as the intake point for every request, manually configuring solutions based on each team's risk tolerance, throughput needs, and product complexity. One person as the connective tissue between an entire Identity service and every line of business that depended on it was a single point of failure, creating a bottleneck that couldn't scale.

By creating a self-service Identity Platform, we could let teams access Identity-related services independently. This means a product owner can come in, describe their needs, and receive a recommended authentication configuration. A developer can view available APIs, review setup parameters, and integrate directly.

This project sits at the center of a company-wide strategic shift toward platform-based architecture led by the CEO, meaning it was high visibility and even presented at the CEO's annual town hall.

**Getting a baseline of the current process**

Before any UI work could begin, I had to understand the current process, its strengths, and its limitations. One of the ways to do this was by shadowing intake calls to observe what questions external teams asked and what information the Identity team needed to configure the correct solution.

The first step was to create a proof-of-concept form to gather all the information a human collected during those intake calls. If this could work without any human touch, it meant a platform was indeed a feasible solution. I found that while the form did get us most of the way there, it still had its limitations. For example, it was long enough to be fatiguing given the volume of questions that had to be answered. Additionally, not everyone had enough knowledge of Identity services to answer every question accurately.

**Facilitating alignment across a room full of decision-makers**

While this was a highly technical project, I found that the hardest part was organizational. A 12-person cross-functional task force was spun up to represent different parts of the Identity ecosystem, each with vastly different competing priorities. As one of the more junior people in the room, I didn't have positional authority but what I had was Process and UX tools.

I co-designed and facilitated several workshops across the project arc, working alongside a senior design manager who provided strategic direction while I executed elements of the sessions. The format was deliberately structured to move from divergence to convergence: group requirements gathering to establish shared context, followed by Crazy 8s rounds to generate ideas quickly without overthinking, followed by presentation and riffing, followed by a second generative round to build on what resonated.

The output of these workshops was documented alignment through a shared artifact that every stakeholder had contributed to. But facilitation alone doesn't create momentum. After every workshop, the hardest question in the room was: what do we actually do next? One tool was creating effort/impact prioritization matrices to translate workshop energy into a defensible roadmap, creating a starting point for future PRDs.

**Influencing without authority**

The tactical reality of working junior in a senior room is that the standard tools of influence, such as title, tenure, and organizational leverage, weren't available which meant I had to get creative.

When stakeholders disagreed, I documented via meeting notes on a shared screen every session, even when we were all in the same room. By making the note-taking visible in real time, everyone could see exactly what was being captured as decisions were made. Once something was written down in front of the whole room, it became much harder to relitigate later.

Since design requirements risked getting deprioritized in the product development lifecycle, I embedded them directly into the PRD to make sure they would get addressed.

When individual influence wasn't sufficient, I escalated strategically, pulling in my design manager to add context and weight without creating conflict.

**UI as a conversation starter**

The initial design work on this project wasn't intended to be built. Instead, it was intended to create something for people to react to. In a problem space this large and this ambiguous, waiting for perfect requirements before designing is a losing strategy since requirements shift and stakeholders change their minds. People discover what they actually want by reacting to something concrete.

By producing relatively lightweight proof-of-concept screens early, the team had something to push against. Stakeholders who had nodded along to a verbal description of a feature could now say: that's not quite what I had in mind. The faster you put something in front of people, the faster the real conversation begins.

These designs were ultimately presented at a Capital One-wide town hall as part of the broader platform strategy, reaching leadership up to the CEO level.

**Process as a tool**

In large, ambiguous systems-thinking projects, the hardest part is alignment across differing priorities. Solving these problems requires the same rigor and intentionality that we bring to designing interfaces: clear objectives, structured methods, iteration, and a willingness to adapt when the approach isn't working.

The lesson I've internalized across more than a decade in this industry: everyone in a corporate environment has access to roughly the same toolkit, and none of these are secret: workshops, frameworks, escalation paths, async documentation. Knowing which tool to wield only comes from practice, trial, and error.

**Reflection** (rewritten, blends influence-without-authority and systems thinking)

I walked into this as the most junior person in a very senior room, without the usual levers of influence. What I learned is that in a problem this big and this ambiguous, the design's real job isn't to be right, it's to give people something concrete to react to. A rough screen, a decision written down where everyone can see it, a workshop that turns competing priorities into a shared artifact. Those are how you move a decision when you can't just make the call yourself, and how you get a room full of people pointed the same direction.

**Testimonial to feature here** (see testimonials section): Michelle Phanthongphay.

---

# CASE STUDY 3 — Project Expedition (placeholder page, featured once written)

**Title**
Rethinking how travelers find a destination

**Placeholder body**
Full case study incoming. Project Expedition is a luxury travel platform I'm the designer on, and it's my most active client work right now. In the meantime, here's a look at the work.

(Add screenshots.)

---

# CASE STUDY 4 — Internal Developer Tool (light study)

**Title**
Designing for the Builder: Redesigning an Internal Developer Tool

**Metadata**
Role: Solo UX Designer
Team: 7 people across design, product, and engineering
Timeline: 6 weeks
Highlighted Tools: Figma, usability testing, WCAG accessibility standards

**Body**

Eno Web Assistant is a Capital One browser extension that uses virtual card numbers to make online shopping more secure. Behind it is the KitchenAid Extension, a developer-facing tool used to create and maintain the rules that make Eno work across thousands of merchant checkout pages.

Testing revealed that the existing extension was error-prone and unintuitive for anyone who hadn't already spent months learning it. I redesigned the extension from low-fidelity sketches through a fully tested high-fidelity prototype, running usability tests at each fidelity level to validate improvements before moving forward. By restructuring the information architecture and updating the visual hierarchy, task completion climbed from 51% to 83% at mid-fidelity, and 94% at high-fidelity.

Having started my career as a developer at Capital One, I understood the tool from both sides, which meant I could design for the technical constraints without losing sight of the user.

---

# CASE STUDY 5 — One AP, American Express (light study)

**Title**
Designing for Self-Sufficiency: The One AP Help Center at American Express

**Metadata**
Role: Solo UX Designer
Team: 5 people across design, product, and engineering
Timeline: 8 weeks
Highlighted Tools: Figma, WCAG accessibility standards

**Body**

One AP is an American Express accounts payable product used by business buyers to manage invoices, payments, and suppliers. When customers hit problems, they called into the customer service line, meaning the representatives were spending significant time fielding questions a well-designed self-service experience could answer independently.

I led the UX design of the One AP Help Center from discovery through handoff, running a two-session workshop with cross-functional stakeholders to align on requirements and generate design directions. From there I ran moderated concept testing with 6 users to validate two competing design patterns before committing to a final direction.

**Testimonials to feature here** (Amex colleagues, see testimonials section): Beth Devine, Rachel Williams Belter.

---

# CASE STUDY 6 — Brand and Identity (light study, placeholder)

**Title**
Brand and identity work

**Placeholder body**
A small collection of logos and marks I've made for clients and side projects, including my own studio, Lati Creative.

(Add marks and client logos.)

---

# ABOUT (placeholder v1, your real rewrite is v2)

I started out as a software engineer, close enough to the build to earn 24 patents, before moving into product design. I left Capital One and came back, so I've seen the same systems from both the engineering side and the design side, and that double vision is what I lead with.

My whole point of view is calibrating friction: knowing when to smooth a path and when a little resistance is the point, because I know what it costs to build the thing on the other side of the screen. I use AI tools throughout my process, but the judgment is mine, and that's the part that matters.

Away from the screen, I make things with my hands, ceramics, crochet, whatever the current hobby is. It's the same instinct as the day job: care about how a thing is made and how it feels to use.

I'm looking for a senior product design role on a mission-driven team. I'm in the DC area and open to remote or relocating for the right one.

---

# OFF THE CLOCK (current copy is fine, photos to come)

**Intro**
The making doesn't stop when the laptop closes. No agenda here. Just the stuff I make for the joy of it. Poke around if you're curious.

**Ceramics**
The same instinct for how things are made shows up away from a screen. I run a ceramics studio with a friend (Seconds). (Add gallery photos.)

**Ceramics mini case study** (optional, from your half-written draft)
The first market we sold at taught me more about UX than I expected. Pricing, display, the path a stranger takes to picking up a mug.

**Currently excited about** (rotating): junk journaling, crochet, watercolor, hand-sewing, knitting, scrapbooking, ceramics.

---

# TESTIMONIALS (from LinkedIn)

Suggested use: cluster of three on About (Beth Devine, Noelle Fair, Michelle Phanthongphay), one dropped into each relevant case study as noted above. The rest are available if you want more.

**Beth Devine** — UX Researcher, worked with Latika at American Express
"Latika is a rare combination of both UX designer and software developer that makes her incredibly valuable in the tech world. She is a fast learner and an amazing team player who genuinely cares about the quality of her work as well as the quality of her relationships with colleagues. I truly enjoyed partnering with her on multiple projects at American Express and would recommend her without hesitation as an asset to any design team."

**Noelle Fair** — Design leader, managed Latika directly
"Latika is a strong thinker. She thinks through the project problems and learns the 'why' behind the work. She works extremely well with stakeholders and team and is a delight to work with. Her optimism and positive attitude make collaborating with her fun. She is a very fast learner and a UX-er at heart."

**Michelle Phanthongphay** — Senior Product Designer, worked with Latika at American Express
"Latika is a collaborative team player who thrives in interdisciplinary environments. She communicates effectively, actively seeks feedback, and could navigate a complex domain and challenging problems with creativity and a positive attitude. Her contributions were invaluable to our projects and demonstrated a strong commitment to achieving the best possible outcomes."

**Rachel Williams Belter** — Digital Accessibility Product Design, American Express
"Latika brings an incredible combination of strategy and creativity. I'm confident her previous experience as a developer has set her up to excel as a designer."

**Joseph Anastasio** — UX Researcher and Designer, managed Latika as an instructor at General Assembly
"She gave students clear, honest design feedback, and straight up taught some of the class lessons. She is a confident presenter, great at pacing a lecture, and handled questions with ease."

**Christie Rossiter** — Product leader, former student of Latika's at General Assembly
"As an instructor, Latika is kind, patient, fun and uplifting. She is able to break down complex topics into simple, digestible pieces of information, and was always someone I felt I could come to for insightful feedback."

**Griffin Chierici** — former student of Latika's at General Assembly
"Latika was my mentor and UX Design instructor. Her warmth, knowledge, and passion for design was an inspiration throughout the course and helped me feel confident entering the job market."

---

# STILL FROM YOU

- Project Expedition full write-up (then it graduates to a featured card)
- About v2 in your own voice (skeleton provided separately)
- Visual assets straight into Claude Design: hand-drawn portrait and stickers, case study visuals, ceramics and hobby photos, client logos, resume PDF
