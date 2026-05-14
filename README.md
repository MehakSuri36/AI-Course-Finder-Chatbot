# AI Course Finder Chatbot

An AI-powered chatbot built using [n8n] that helps users discover the best online courses based on their interests, skill level, preferred platform, and career goals.

Unlike many AI recommendation systems that overwhelm users with too many options or provide incomplete information, this chatbot delivers a clear, structured, and detailed overview of courses in a single response. Instead of forcing users to ask multiple follow-up questions, it provides everything important upfront to help users make faster and smarter learning decisions.

## Unique Features

Most AI systems:

* Recommend random or excessive courses
* Provide incomplete information
* Create confusion about which course to choose

This chatbot solves that problem by offering:

* Focused and relevant course recommendations
* Complete course overview in one go
* Clear explanation of why a course is recommended
* Simple comparison between courses
* Guidance on which course should be taken first
* Important details users usually forget to ask

## What the Chatbot Provides

* Course difficulty level
* Prerequisites required
* Skills covered
* Estimated completion time
* Free vs paid information
* Certificate availability
* Beginner-friendly guidance
* Best platform recommendation
* Real-world usefulness of the course
* Suggested learning roadmap after course completion

Instead of simply sharing course links, the chatbot acts like a personal learning advisor.

## Tech Stack

* **Automation Platform:** n8n
* **AI Integration:** OpenAI API
* **Backend Logic:** Workflow automation
* **APIs Used:** Search APIs

## How It Works

1. User enters a topic they want to learn.
2. The chatbot asks follow-up questions such as:

   * Preferred platform
   * Skill level
   * Budget
   * Career goals
3. n8n processes the workflow.
4. AI analyzes the request and searches course platforms.
5. The chatbot returns:

   * Best course options
   * Full course overview
   * Learning recommendations
   * Suggested roadmap

All in one clean and easy-to-understand response.
