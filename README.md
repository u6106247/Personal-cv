# HYPERMEDIA PROJECT, PT. 1: Documentation
**Author:** David Soler Flores  
**UdG Code:** u6106247  
## Project analysis

### 1. User profile

**David Soler Flores, 20 years old, Computer Engineering student and researcher at the University of Girona (UdG)**

David is a Computer Engineering student at the University of Girona who started his degree in 2024 and, since March 2026, also works as an assistant in the LAI (Logic and Artificial Intelligence) research group. He lives in Santa Coloma de Farners and speaks Catalan and Spanish at a native level (C2), English (B2) and Italian (A2). He is looking for internships, research opportunities and his first jobs related to computer science, especially in areas close to logic, algorithms and artificial intelligence, so that he can gain professional experience while he completes his degree.

His main goals are to present his technical skills and academic background clearly, to let recruiters and professors check his work directly through his GitHub profiles, and to make a good first impression by showing that he is organized, responsible and capable of working in a team. To achieve this, he needs a CV that is clear, professional and easy to read, which shows the programming languages and tools he knows (C/C++, Python, Java, JavaScript, VHDL, LaTeX, MiniZinc, R, HTML and CSS), his contact information, his education, his work experience and his projects.

As a student with limited professional experience, he cannot rely on a long career. For this reason, he needs to highlight his university projects (a schedule generator using backtracking and a SAT solver) and his research work, and also include his first jobs (youth brigade for the town council and bicycle mechanic's assistant), which are not related to his field but show responsibility, teamwork and customer service. The CV is therefore designed as a single structured page that lets a recruiter identify his strengths in a few seconds, and that works on a computer and on a mobile phone, because many people open links from their phones.

### 2. Information architecture

I designed the website as a single-page static CV, so that visitors can find everything without navigating between different pages. The information is distributed in two main areas, placed side by side on large screens: a sidebar on the left and a content area on the right.

The sidebar groups the personal information and the quick-reference data. At the top, it shows my circular photograph next to my name and a short professional description ("Computer Engineering student and researcher in UdG"), which introduces me before anything else. Below it, I placed the contact details as separate cards: e-mail, phone number, city and two GitHub profiles (my personal account and my university account). Each one has its own icon so it can be recognised at a glance, and the e-mail and GitHub entries are links, so a recruiter can write to me or open my repositories with one click. The sidebar ends with two cards, one for the technical skills and another for the languages with their levels. I put them here because they are short lists that a recruiter usually wants to check quickly, and having them next to the photo and the contact information creates a compact "identity card" of the candidate.

The right area contains the longer content, ordered from most to least relevant for a recruiter. First comes the experience, with the company or position, the dates and a list of responsibilities for each job: Youth Brigade (2024), Country Bikes (2025) and my current position in the LAI research group at UdG. Second comes the education, in chronological order, from compulsory secondary education to my current BSc in Computer Engineering. Finally, the projects section describes my two main projects, the schedule generator using backtracking and the SAT solver, each with a short list of what it does. The schedule generator links to its GitHub repository.

All sections use the same pattern (a heading, a date when needed and a bulleted list), which makes the page predictable and easy to scan. On small screens, the two areas are stacked in a single column with the sidebar first, so the order of reading stays the same.

### 3. Visual design

I wanted a design that looks professional and modern, but also warm and personal, so I used a limited colour palette. The page background is a dark burgundy (`#442222`). On top of it, the sidebar and its cards use semi-transparent white (30% opacity), which gives a soft layered effect without adding more colours. The main content area is a plain white card, which contrasts strongly with the dark background and makes the long texts comfortable to read. The section headings are dark grey (`#545454`) rounded labels with white text and a thin line that extends to the edge of the card, and secondary information such as dates and project descriptions uses a medium grey (`#6b6b6b`) to create hierarchy against the black titles.

I used two typefaces from Google Fonts to separate the two areas. Montserrat is used in the content area for titles and body text because it is clean, geometric and very readable. Inter is used in the sidebar because it is designed for screens and stays legible in different weights, which I combine in the name and description: light for normal words and bold for "Soler Flores", "student" and "researcher". Different font sizes and weights give the page its visual hierarchy, so section headings, job titles, dates and bullet points can be told apart immediately.

For the layout, I used CSS Grid to create the two columns of the page and Flexbox for the elements inside them: the photo and the text in the profile, the icon and text of every contact card, and the section headings with their line. Other properties that were important for the result are `border-radius` for the rounded corners and the circular photograph, `object-fit` and `object-position` to crop and position the photo, `aspect-ratio` to keep its proportions, `gap` for spacing, and a media query at 800 px that turns the layout into a single column for mobile devices. Colours and the main radius are defined as CSS variables in `:root`, so the design can be changed easily.

Lastly, the icons were exported from Figma as PNG images, and the links get an underline when the mouse goes over them, so it is clear what can be clicked. In general, I think the design is consistent, clear and attractive, and that it presents my profile in an organized way.

### 4. Link to the Figma project

- https://www.figma.com/design/r1rhSko8KpVrffru9YMxFM/CV---David-Soler-Flores?node-id=1-2&t=XrHOnoACWv4zgao6-1

## Project structure

```
├── index.html
├── style.css
├── README.md
└── img/
    ├── foto.jpg
    ├── mail.png
    ├── call.png
    ├── location.png
    └── github.png
```

To see the website, open https://u6106247.github.io/Personal-cv/ in any web browser. No installation or build step is needed.