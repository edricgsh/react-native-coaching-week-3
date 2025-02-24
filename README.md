# Edric Module 5 Coaching Week 3

## **Observations on Common Issues During the Presentation**

### **1. Struggling with Expo External Libraries on Different OS**

This is a tricky issue, and I’ve noticed many of you encountering roadblocks here. Here’s what I’d suggest:

- **Log everything**: When something breaks, print out the logs and errors. This will help you pinpoint the issue.
- **Permissions are tricky**: Different OS versions handle permissions differently. For example, Android 13+ requires you to submit your app for review before asking users for access to their Media library. The code you write will need to be adjusted for different OS versions in certain scenarios.
- **Test on multiple devices**: Even the same OS can behave differently across devices. Don’t assume it’ll work the same everywhere!

---

### **2. Creativity in Applying Knowledge**

I’ve been really impressed with some of the projects you’ve built! Here are a few highlights:

- **React Native Paper**: Some of you used this to create beautiful UIs and even built custom hooks to manage shared logic. Great job!
- **Motion Detection Quiz App**: This was a creative use of what we learned in class. It’s awesome to see you thinking outside the box.

Keep this energy, and keep pushing yourselves. Creativity is what sets you apart in the job market.

---

### **3. Backend API and Optimistic Updates**

I noticed some of you are using backend APIs and implementing CRUD operations in your app. Here’s a key tip to improve user experience:

- **Optimistic Updates**: Update the UI first, then sync with the backend. If the backend fails, revert the UI. This way, users don’t have to wait 1-2 seconds for updates to reflect. It’s a small change but makes a big difference!

---

## **Other Topics to Discuss**

### **1. Best Practices for Collaborating on GitHub**

Working in a team can be messy if you’re not on the same page. Here’s how to keep things smooth:

- **One Repo, Multiple Branches**: Use a single repository with feature branches. Each feature should have its own branch, and you’ll merge into the main branch via pull requests (PRs). You can revisit Git Flow, GitHub Flow, or Trunk Flow in module 4 and select the one that you think is most suitable for your team.
- **Protect the Main Branch**: The main branch should be protected, and PRs should require at least 1-2 approvals before merging.
- **Forking Isn’t Always the Answer**: Forking is useful if you want to maintain your own version of a library (e.g., forking React to make company-specific tweaks). But for team collaboration, stick to branches.

---

### **2. Making Apps Production-Ready**

Building something that works is one thing; making it production-ready is another. Here’s my advice:

- **Focus on One App**: Instead of building 10 demo apps, focus on one useful app. Push it to production, optimize it, and learn from the process.
- **Design Thinking Matters**: As an interviewer, I care more about how you approach problems and design solutions than the specific libraries you use. Show me you can think critically and solve real-world problems.
    - **Example**: If you’re building a video player, I care about how you load the video so that the user has the best viewing experience. How do you design the app to remain user-friendly for people with poor internet connections? When you ask yourself more questions, you’ll naturally discover more problems to solve and their respective solutions. This is how you grow as an engineer and what interviewers look for.

---

## **Resources to Help You Excel**

### **1. Tech Interview Handbook** [Check it out here](https://www.techinterviewhandbook.org)

This is a fantastic resource written by a Meta engineer. It covers everything from resume writing to salary negotiation.

- **Grind 75**: A curated list of LeetCode questions that cover a wide range of topics and difficulties. Perfect for interview prep! [Check it out here](https://www.techinterviewhandbook.org/grind75/?weeks=1)

### **2. My Job Search Strategies**

I wrote a post summarizing my 7-month job search journey. It’s packed with tips and lessons I learned along the way. [Read it here](https://substack.com/home/post/p-136897683)

---

## **Personal Advice**

### **1. Build Interesting Projects and Market Yourself**

- **Solve Real Problems**: Use your domain expertise to build something that solves a tough problem in your industry.
- **Tell a Story**: Once you’ve built it, share it with a compelling narrative on LinkedIn. Startup founders love people who are self-driven and can think creatively. This is how you can kickstart your career as a software engineer.

### **2. Use AI as a Tool to Level Up**

AI tools can help you learn and work faster. Here are a few I recommend:

- **Claude**: Great for long code generation.
- **Cursor**: A fantastic code editor with AI-powered features. It’s super fast if you don’t want to leave your editor. You can keep "tabbing," and the autocomplete will blow your mind. But definitely don’t overuse it.
- **DeepSeek**: Another tool to help you with code generation.

### **3. Seek Mentorship**

Don’t underestimate the value of learning from others and working with someone experienced in the industry. Here are two platforms I recommend:

- **Mentorcruise**: Connect with mentors in tech. It’s very useful if you want to work long-term with a senior software engineer. Some mentors charge less than $150/month, which I personally feel is good value for money. But you can decide for yourself. [Check it out here](https://mentorcruise.com/)
- **Adplist**: Another great place to find mentors and get career advice. It’s free to meet some mentors on an ad-hoc basis. You can pay to have a long-term relationship with some of the mentors. [Check it out here](https://adplist.org/)# react-native-coaching-week-3
