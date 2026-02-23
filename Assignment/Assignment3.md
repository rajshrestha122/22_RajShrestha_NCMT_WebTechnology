
# Chapter 3: Website Structure Design

## Group A: Short Questions (2 Marks Each)

### 1. Define Information Architecture (IA)?
Information Architecture (IA) is simply the way we *organize and arrange* all the information and pages on a website so that people can easily understand the
structure and quickly find what they are looking for.  

Think of it like making a very clear map of a big shopping mall — you decide where each shop goes, how the paths connect, what signs to put, and how to name
everything so visitors don't get lost even if it's their first time.

### 2. What is a "Wireframe"?
A wireframe is like a *rough pencil sketch* of a webpage.  
It shows only the basic structure and placement of things:  
- Where the logo goes  
- Where the menu will be  
- Where the main content area is  
- Where buttons, images, and forms will sit  

It doesn't have colors, real photos, or fancy fonts — just boxes, lines, and labels. It's the first planning step before making the beautiful final design.

### 3. Explain the concept of "Cognitive Friction" in web design
Cognitive friction means the *extra mental work* a person has to do when using your website because something is confusing or not obvious.  

Examples of high cognitive friction:  
- Navigation menu is hidden  
- Buttons don't look like buttons  
- Labels are very vague ("Click here" instead of "Download Brochure")  
- Too many choices at once  
- Form asks strange questions without explanation  

When cognitive friction is high → users feel annoyed, take longer, make mistakes, and most importantly — they leave the website very fast.

### 4. Why should URL slugs use hyphens instead of underscores?
There are two main reasons:

1. *Search Engines (especially Google) like hyphens better*  
   Google reads hyphen (-) as a space between words.  
   So best-running-shoes is understood as three separate words → better for SEO.  
   But underscore (_) is seen as one single long word → not good for ranking.

2. *Humans also read hyphens easier*  
   contact-us looks much more natural than contact_us  
   Most people are used to seeing hyphens in URLs.

*Best practice (2025–2026 standard):* Always use hyphens, lowercase letters, and keep slugs short & meaningful.

## Group B: Long Questions (4 Marks Each)

### 5. Compare and contrast Hierarchical (Tree) structure and Linear (Sequential) structure. Give an example of when to use each.

*Hierarchical (Tree) Structure*  
Imagine a big tree:  
- One main trunk (Home page)  
- Then big branches (main categories)  
- Then smaller branches (sub-categories)  
- Then leaves (individual pages)  

Users can choose different paths and go as deep as they want.

*Linear (Sequential) Structure*  
It's like a straight road with clear steps:  
Page 1 → Page 2 → Page 3 → Page 4  
No side roads, no going back easily, just forward (sometimes backward with "Previous").

*Quick Comparison Table*

| Point                     | Hierarchical (Tree)                  | Linear (Sequential)                |
|---------------------------|--------------------------------------|------------------------------------|
| Structure                 | Branches in many directions          | One straight line                  |
| User freedom              | High – can explore freely            | Low – must follow the sequence     |
| Best for                  | Websites with many topics/categories | Step-by-step processes/guides      |
| Risk of confusion         | Can be high if badly organized       | Very low                           |
| Number of pages usually   | Medium to very large                 | Small to medium                    |
| Real-life feeling         | Shopping mall / University website   | Cooking recipe / Online form       |

*Best time to use each:*

- *Use Hierarchical* when you have lots of different sections  
  Example: Daraz, Amazon, university website, news portal  
  → User starts at home → chooses Electronics → then Mobile Phones → then Samsung → then particular model

- *Use Linear* when the user must follow exact steps in order  
  Example: Online exam registration (Step 1: Personal info → Step 2: Documents → Step 3: Payment → Step 4: Confirmation)  
  or any tutorial like "How to install Windows 11 step-by-step"

### 6. Explain the "Three-Click Rule" and its significance in User Experience (UX) design.

The *Three-Click Rule* is a very popular idea that says:  
"Any important information or page on your website should be reachable in maximum *3 clicks* from the home page."

*Why people loved this rule?*  
- In early days of internet (2000s), people were not very patient  
- If it took 5–6 clicks to reach something, many users would get irritated and leave  
- So designers tried very hard to make websites "flat" (less deep levels)

*What is the real situation in 2026?*  
- It's *not a strict rule* anymore  
- Sometimes 4–5 clicks are okay *if* the navigation is very clear, logical, and helpful  
- Modern websites use powerful search bars, mega menus, breadcrumbs, and filters — so even deeper pages feel easy to reach

*Why it is still important in UX?*  
- It reminds designers to *put important things close to the surface*  
- It helps reduce user frustration and anger  
- Websites that follow this idea (or similar thinking) usually have:  
  → Lower bounce rate  
  → More time spent on site  
  → More purchases/forms filled  
  → Happier visitors

So even today, when planning a site, many designers still ask themselves:  
"Can most users reach what they want in 3 clicks or less?"

### 7. "Plan before you do." Explain how tools like Card Sorting and Flowcharts help in planning a website's structure.

"Plan before you do" means: *never start designing or coding without a clear plan first*.  
Building a website without planning is like constructing a house without any map — it will have many problems later.

Two very powerful planning tools are:

*1. Card Sorting*  
- You write each main topic/page/content item on a small card (real cards or digital tools like Miro/Optimal Workshop)  
- Then you ask real users (or at least 5–10 people) to group these cards in the way that makes most sense to them  
- Two main types:  
  - *Open Card Sort* → Users make their own groups and name them (best for discovering how people really think)  
  - *Closed Card Sort* → You give ready-made category names and users just put cards into them (checks if your idea matches users' thinking)  

*Result?* You get the most natural menu structure, category names, and hierarchy that real people understand — not just what the designer thinks is good.

*2. Flowcharts*  
- Simple diagram with boxes (pages) and arrows (connections)  
- Shows how a user can move from one page to another  
- You can quickly see:  
  - Is there any dead-end page?  
  - Is some path too long and confusing?  
  - Are important pages missing?  
  - Is there a loop that can trap users?

*Why both tools are magic together?*  
- Card Sorting → tells you *how to group* things (menu structure)  
- Flowchart → tells you *how pages should connect* (user journeys)  

When you use both before touching any code or design software → you save a lot of time, money, and redesign work later.

## Group C: Scenario-Based Questions (5 Marks Each)

### 8. You are designing a website for a University. It has hundreds of pages (Admissions, Departments, Alumni, News). Which structural model would you choose?
Draw a rough diagram and justify your choice.

*Best choice: Hierarchical (Tree) Structure*

*Why this is the perfect choice for a university website?*  
- Universities have many completely different sections (Admissions, Academics, Student life, Research, Alumni, News…)  
- Each section has many sub-sections (e.g., under Academics → many departments → many programs)  
- Different people need different things: students want courses, parents want fees, alumni want events  
- Hierarchical structure allows logical grouping, easy expansion when new departments come, and familiar navigation (everyone has seen this style on big websites)  
- Also helps create clean, keyword-rich URLs which Google loves

*Simple Text Diagram of the Structure*
Homepage (Main Gate) ├── Admissions & Fees │   ├── Undergraduate Programs │   ├── Master's Programs │   └── Scholarship & Financial Aid ├── Academics │  
├── Faculties & Departments │   │   ├── Faculty of Science │   │   ├── Faculty of Management │   │   └── Faculty of Law │   └── All Courses & Syllabus ├──
Student Life │   ├── Hostels & Accommodation │   ├── Clubs & Events │   └── Sports & Gym ├── Research & Innovation ├── Alumni Network │   ├── Alumni Events │ 
└── Donation & Support └── News & Notices ├── Latest University News └── Exam & Result Notices

This kind of tree structure feels natural, scalable, and user-friendly for a big institution like a university.

### 9. A user visits a website but leaves within 10 seconds because they cannot find the navigation menu, which is hidden behind a small icon on a desktop screen.
Analyze this design failure using the "KISS" (Keep It Simple, Stupid) principle.

*KISS Principle in simple words:*  
"Keep It Simple, Stupid" → Don't make things more complicated than necessary.  
The simpler the design, the faster people understand it and the happier they are.

*Why this is a big KISS failure?*  
- On *desktop computers* there is a lot of space (wide screen)  
- Everyone expects to see the main menu clearly written across the top (Home, About, Services, Contact, etc.)  
- Hiding the entire navigation behind a tiny hamburger icon (☰) is *completely unnecessary* on desktop  
- Forcing users to search and click an icon first → creates instant confusion  
- Most users think: "Where is the menu? Is this site broken?" → leave in <10 seconds

*What KISS would suggest instead?*  
- On desktop → show full horizontal menu clearly (simple & visible)  
- Only on mobile phones/tablets → use hamburger icon (because space is really limited there)  
- Simple = visible + predictable = users understand in 1 second = they stay longer

This mistake is one of the most common reasons for very high bounce rates in 2025–2026.

### 10. An e-commerce website has a URL structure like www.shop.com/prod?id=55&cat=9. Explain why this is bad for both users and Search Engines (SEO), and propose
a better structure using Page Slugs.

*Why this URL is terrible?*

*Problems for Users*  
- Looks like computer code, not human language  
- No one can understand what product it is just by reading the link  
- Very hard to remember or share with friends  
- Looks cheap/unprofessional (trust issue)

*Problems for SEO (Google & Search Engines)*  
- No real keywords → Google doesn't know this page is about "Samsung Galaxy S25"  
- Query parameters (?id=55&cat=9) are usually ignored or given very low importance  
- If same product shows with different parameters → duplicate content problem  
- Very hard to rank high for normal searches like "buy samsung galaxy s25 online"

*Much better modern URL using slugs (2026 standard)*

*Recommended examples:*
https://www.shop.com/mobiles/samsung-galaxy-s25-ultra
*Why this is 100× better?*  
- Contains important keywords people actually search for  
- Looks clean, professional, and trustworthy  
- Easy to read, remember, and share  
- Google loves it → much better ranking chance  
- Higher click-through rate in search results  
- Uses hyphens (-) between words (SEO best practice)

*Quick tip:* Keep slugs short, meaningful, lowercase, and always use hyphens — never underscores or strange characters.
