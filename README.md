# Resume-Tailoring
An  n8n automation workflow designed to bridge the gap between static professional resumes and high-demand, specific job descriptions. This engine utilizes agentic AI logic to dynamically restructure, rebrand, and optimize CVs for ATS (Applicant Tracking Systems) and human recruiters.

🚀 The Mission Modern hiring is moving fast. Most candidates fail because their resumes don't speak the specific "language" of a job description. Nexora Labs built this engine to automate the "scrappy prototyping" of high-impact resumes, ensuring every application is perfectly aligned with the employer's mission and technical toolbox.

🛠️ Technical Stack Orchestration: n8n (Self-hosted)

LLM Intelligence: Google Gemini 1.5 Flash / Groq (Llama 3.3 / Qwen)

Data Extraction: PDF Binary Parsing & JSON Transformation

Frontend-to-Backend: Webhook triggers for real-time processing

Document Generation: Dynamic HTML/CSS to PDF conversion

🧠 Key Features Contextual Rebranding: The engine analyzes the philosophy of the hiring company and re-angles the candidate's summary and title (e.g., transforming a general "N8N Engineer" into a "Junior AI Automation Engineer" for specific roles).

Automated Skill Mapping: Scans the Job Description for specific tools (like Cursor, Claude Code, or Python) and cross-references them with the candidate's background to build a custom "Toolbox" section.

Binary Data Handling: Efficiently manages PDF uploads and downloads via webhooks, ensuring a seamless user experience.

Agentic Decision Making: Uses structured prompts to ensure the AI doesn't just swap words, but actually "thinks" about how to frame the candidate's experience to solve the employer's specific problems.

📂 Workflow Structure Trigger: Webhook receives PDF (Original CV) + Text (Job Description).

Extraction: Extracts raw text from the binary PDF file.

Intelligence: AI Agent processes the resume against the JD using high-context models.

Formatting: Transforms Markdown output into a structured HTML/CSS template.

Output: Converts HTML to a professional PDF and returns it as a binary download.

📈 Status: MVP Currently, the "intelligence" engine is fully functional. We are currently refining the CSS templates to offer multiple professional visual layouts.
