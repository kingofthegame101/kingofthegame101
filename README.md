const profile = {
  name: "Quyen Tang",
  role: "Finance & Accounting Student | Developer",
  tagline: "I understand the business problem. I can also build the solution.",

  education: [
    "BSc Accounting & Finance — University of Birmingham (via SIM, Singapore)",
    "CS50x — Harvard's Introduction to Computer Science ✅",
  ],

  techStack: {
    languages: ["C", "Python", "JavaScript", "HTML", "CSS", "SQL"],
    concepts: ["Frontend", "Backend", "REST APIs", "JSON", "GUI"],
    tools:    ["Google Apps Script", "Git", "GitHub"],
  },

  currentProjects: [
    {
      name: "🏸 Badminton App",
      description:
        "Web app for booking badminton courts and analyzing rally performance from match data.",
    },
    {
      name: "📊 Automated Sales System",
      description:
        "Automates cold-lead outreach and tracks the entire pipeline inside Google Sheets.",
      tech: "Google Apps Script + Sheets API",
    },
  ],

  languages:   ["Vietnamese", "English", "Mandarin", "French"],
  experience:  ["Sales Internship", "Operations Internship"],
  softSkills:  ["Business thinking", "Communication", "Adaptability"],

  links: {
    linkedin: "https://linkedin.com/in/YOUR_PROFILE",
    github:   "https://github.com/YOUR_USERNAME",
  },

  openTo: "Tech internships where business sense meets code 🚀",
};

console.log(`Hi there 👋 I'm ${profile.name}`);
console.log(`💡 ${profile.tagline}`);
console.log(`📬 Open to: ${profile.openTo}`);

