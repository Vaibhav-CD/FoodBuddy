🥗 FoodBuddy: AI-Native Nutritional Intelligence

The open-source co-pilot for transparent grocery shopping.

FoodBuddy bridges the gap between complex food labeling and consumer health. By leveraging multi-modal AI, it transforms raw ingredient lists into actionable health scores and comparative data in real-time.

🛠 Tech Stack
Frontend: Next.js (App Router), TypeScript, Tailwind CSS
AI & Logic: Google Gemini Pro, Prompt Engineering
Vision/Audio: Tesseract.js (OCR), Web Speech API
Persistence: Browser Local Storage & State Management

🚀 Key Engineering Features
1. Intelligent Label Parsing (OCR)
Uses Tesseract.js to extract structured text from noisy product images. The extracted data is then processed through an LLM-based cleaning pipeline to normalize chemical names and additives.

2. Deep Analysis Engine
A proprietary scoring logic that evaluates products on a 0-100 Health Scale.

The Verdict: Real-time ratings (Excellent, Moderate, Avoid).
Ingredient X-Ray: Instant breakdown of Natural vs. Processed additives.
Dietary Guardrails: Automated flagging for Vegan, Gluten-Free, and Keto compliance.

3. Compare Mode (Decision Engine)
Enables head-to-head comparisons between two products. It generates a Key Difference Grid to highlight hidden sugars, synthetic preservatives, and nutritional density gaps.

4. Accessibility First
Integrated Voice-to-Text capabilities for hands-free queries and a Mobile-First UI optimized for one-handed use during in-store shopping.
