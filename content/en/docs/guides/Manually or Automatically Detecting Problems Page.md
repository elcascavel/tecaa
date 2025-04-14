---
title: "Manually or Automatically Detecting Problems Page"
description: "How to detect understandability issues in web accessibility, both manually and automatically."
summary: "A guide on detecting accessibility issues related to understandability."
date: 2023-09-07T16:04:48+02:00
lastmod:  2025-04-02
draft: false
weight: 4
toc: true
seo:
  title: "Manually or Automatically Detecting Problems Page" # custom title (optional)
  description: "A detailed guide on how to manually and automatically detect accessibility issues affecting the understandability of digital content." # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

## Introduction
Ensuring that web content is understandable is a key aspect of web accessibility. Users, especially those with cognitive and learning disabilities, rely on clear and predictable content to navigate and comprehend digital information effectively. To maintain compliance with the Web Content Accessibility Guidelines (WCAG), it is essential to detect and address understandability issues. This can be done manually by experts and users, or automatically using accessibility evaluation tools.

## Manual Detection of Understandability Issues
Manual testing is crucial because some accessibility issues are subjective and require human judgment. This method allows testers to experience content as users do, ensuring that information is clear, consistent, and well-structured.

### Common Manual Testing Methods
1. **Heuristic Evaluation**
   - Experts review content against WCAG guidelines.
   - Checks for jargon, complex sentence structures, and ambiguous phrasing.
   
2. **User Testing**
   - Real users, especially those with cognitive disabilities, assess readability and navigation ease.
   - Feedback is gathered to improve content clarity and presentation.
   
3. **Content Readability Analysis**
   - Ensures that language is simple and accessible.
   - Readability tests, such as Flesch-Kincaid or Gunning Fog Index, are used to measure text complexity.

### Tools for Manual Testing
- **Hemingway Editor**: Highlights complex sentences and difficult words.

<img src="/images/hemingway.gif" alt="Hemingway Tool Example Gif" width="700" style="display: block; margin: 0 auto;">


---


- **Readability Formulas**: Online tools that assess reading difficulty levels.

<img src="/images/readabilityformulas.png" alt="Readibility Score Tools Examples" width="700" style="display: block; margin: 0 auto;">

- **Browser Extensions**: Some extensions identify overly complex content and readability issues.

## Automatic Detection of Understandability Issues
Automated tools can quickly analyze content and identify potential problems, making them useful for initial testing and large-scale evaluations.

### Types of Automated Tools
1. **Linter Tools**
   - Detect improper HTML and ARIA attributes that affect accessibility.
   - Example: **axe-core**, **Lighthouse**.

2. **Readability Analyzers**
   - Assess text complexity using algorithms.
   - Example: **Readability Test Tool**, **Microsoft Word Readability Statistics**.

3. **AI-Based Tools**
   - Utilize machine learning to evaluate text clarity and content predictability.
   - Example: **Grammarly’s clarity suggestions**, **LanguageTool**.

### Limitations of Automated Detection
- Automated tools may not detect contextual readability issues.
- Cannot fully assess user experience or intent.
- Best used in combination with manual testing.

## Best Practices for Detection & Improvement
- Combine manual and automatic methods for comprehensive evaluation.
- Regularly update content to maintain clarity and avoid outdated terminology.
- Use plain language and provide alternative formats, such as easy-read versions.
- Follow WCAG recommendations and ensure predictable navigation.

## Compliance Levels (A, AA, AAA)
### **Level A**
- Content must not be overly technical or ambiguous.
- Example: Avoiding acronyms without explanations.

### **Level AA**
- Ensuring consistent navigation and clear instructions.
- Example: Providing definitions for uncommon terms.

### **Level AAA**
- Requires highly readable content with supplementary explanations.
- Example: Offering summaries for complex content or alternative easy-read versions.

## Conclusion
Detecting and resolving understandability issues is crucial for creating an inclusive web experience. Combining manual and automatic testing ensures compliance with WCAG standards and improves user experience for all audiences. By integrating accessibility testing into the development process, websites can become more usable, predictable, and comprehensible for everyone.

## Further Reading
- [Web Content Accessibility Guidelines (WCAG) 2.2](https://www.w3.org/WAI/WCAG22/quickref/)
- [Diátaxis Framework - How-To Guides](https://diataxis.fr/how-to-guides/)