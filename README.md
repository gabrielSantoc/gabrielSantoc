# 💻 About Me

```typescript
interface Developer {
  name: string;
  role: string;
  email: string;
  phone?: string;
  location?: string;
  experience?: number;
}

const developer: Developer = {
  name: "Gabriel Santoc",
  role: "Flutter Developer || Backend Developer", 
  email: "gabrielsantoc05@gmail.com",
};


// Work Experience
// Work Experience
interface Job {
  company: string;
  position: string;
  duration: string;
  tech: string[];
}

const experience: Job[] = [
  {
    company: "EMS. Group Inc.",
    position: "Software Developer Intern",
    duration: "Feb - Mar 2025",
    tech: ["HTML", "CSS", "Javascript", "TypeScript", "Node.js", "Express", "Langchain", "FAISS", "mySQL", "CentOS"]
  },
];

// Featured Projects
// Featured Projects
interface Project {
  name: string;
  description: string;
  tech: string[];
  github?: string;
  demo?: string;
}

const projects: Project[] = [
  {
    name: "myEUC",
    description: "AI Powered student handbook mobile application",
    tech: ["Flutter", "Dart", "Supabase", "Express.js", "Langchian", "FAISS"],
    github: "https://github.com/gabrielSantoc/myEUC-x-Supabase",
  },
  {
    name: "Scheduled Push Notification API",
    description: "A RESTful API that automatically sends push notifications for upcoming events in the myEUC app.", 
    tech: ["Node.js", "Express.js", "Javascript", "Docker", "Supabase"],
    github: "https://github.com/gabrielSantoc/Push-Notification-Service-API"
  },
  {
    name: "EUScheduler",
    description: "An offline class schedule viewer mobile application designed for university students.",
    tech: ["Flutter", "Dart", "SQLite", "Supabase"],
    github: "https://github.com/gabrielSantoc/EUCcheduler",
  }
];

// Education
// Education
interface Education {
  degree: string;
  school: string;
  startYear: number;
  endYear: number;
}

const education: Education = {
  degree: "Bachelor of Science in Computer Science",
  school: "Manuel S. Enverga University",
  startYear: 2021,
  endYear: 2025,
};

// Contact Information
// Contact Information
const contact = {
  email: developer.email,
  linkedin: "https://www.linkedin.com/in/gabriel-santoc-827307281",
  github: "https://github.com/gabrielSantoc",
  portfolio: "https://gabrielsantoc.vercel.app"
};

// Current Status
// Current Status
const status = {
  seekingOpportunities: true,
  availableForRemote: true,
  preferredRole: ["Backend Dev", "Flutter Dev", "Any"],
  startDate: "Immediately"
};

console.log(`📧 Contact me at: ${contact.email}`);
