# tech-career-blog

Practical writing on AI platforms, software architecture, and building a senior engineering career. Written for engineers, by engineers.

## Structure

```
tech-career-blog/
├── index.html        # Landing page — lists all posts
└── blogs/            # Individual post files
    └── chatbots-vs-agents-blog.html
```

## Posts

| Title | Date | Tags |
|---|---|---|
| [Your AI Job Search Has Two Modes. Most People Use Zero.](blogs/job-hunt-intel.html) | April 2026 | SRE, job-search, AI-agents, kimi-k2.5, claude, career |
| [AI Chatbots vs. AI Agents: Stop Conflating Them](blogs/chatbots-vs-agents-blog.html) | April 2026 | AI, AI-agents, platform, software-design |

## Adding a New Post

1. Write the post as a standalone HTML file and drop it in `blogs/`
2. Add a new `.post-card` block in `index.html` pointing to the new file

## Viewing Locally

No build step. Open `index.html` directly in a browser.
