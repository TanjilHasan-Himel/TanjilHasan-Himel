<div align="center">
  <a href="https://tanjilhasanhimel.me/"><img src="assets/profile-banner.png" width="100%" alt="Tanjil Hasan Himel — Developer, Analytical Thinker, Problem Solver" /></a>
  <p><a href="https://tanjilhasanhimel.me/"><img src="assets/toolkit/portfolio.png" width="88" height="26" alt="Portfolio" /></a> <a href="https://www.linkedin.com/in/tanjilhasanhimel/"><img src="assets/toolkit/linkedin.png" width="66" height="26" alt="LinkedIn" /></a> <a href="https://remote.io/tanjilhasan"><img src="assets/toolkit/remote-io.png" width="76" height="26" alt="Remote.io" /></a> <a href="https://www.fiverr.com/tanjilhasan03/"><img src="assets/toolkit/fiverr.png" width="70" height="26" alt="Fiverr" /></a> <a href="mailto:taanjilhasan@gmail.com"><img src="assets/toolkit/email.png" width="67" height="26" alt="Email" /></a></p>
</div>About me
I am a Computer Science & Engineering student at Varendra University, Bangladesh. I build web and mobile applications, connect services and explore how software can improve business operations. My background in radio broadcasting also shapes how I communicate and tell stories.

Open to: Entry-level roles, internships, paid freelance projects and remote collaboration.
Featured capstone — SmartLib / Digital Library Assistant
<table>
<tr><td width="38%" valign="top"><img src="assets/projects/smartlib.png" width="100%" alt="Digital Library Assistant project artwork" /><p><b>B.Sc. CSE Final Year Project · July 2026</b></p><p>Varendra University, Department of CSE</p><p><b>Supervisor:</b> Md. Arshad Wasif, Lecturer, Dept. of CSE</p></td><td width="62%" valign="top"><h3>One platform for students, librarians and institutions</h3><p>Multi-tenant library management with a student mobile app, librarian dashboard, super-admin dashboard and centralized REST backend.</p><p><b>My role:</b> Team lead and core developer — system architecture, mobile development, core implementation, testing and documentation.</p><p><img src="assets/toolkit/flutter.png" width="75" height="26" alt="Flutter" /> <img src="assets/toolkit/django.png" width="78" height="26" alt="Django" /> <img src="assets/toolkit/mongodb.png" width="98" height="26" alt="MongoDB" /> <img src="assets/toolkit/gemini-api.png" width="103" height="26" alt="Gemini API" /></p><p><b><a href="https://tanjilhasanhimel.me/smartlib/">Read project case study</a> &nbsp;·&nbsp; <a href="https://www.youtube.com/watch?v=SxjPciMqh5Y&amp;t=816s">Watch project demonstration</a></b></p></td></tr>
</table><details>
<summary><b>Explore architecture &amp; implementation</b></summary>System area	Implementation
Multi-tenant architecture	Separate institutional data and administration; configurable borrowing limits, renewal periods, grace periods and fines; audit logging.
Institutional onboarding	CSV import and university-specific API integration (including a separate integration server); Django database routing to legacy SQL student records.
Identity & access	JWT access/refresh tokens, configurable login validity, role-based access control (Student, Librarian, Super Admin), email OTP and 30-second rotating HMAC-SHA256 QR IDs.
Library operations	Catalog and stock management, checkout and return, expected return-date estimation, digital receipts and PDF reporting.
AI assistant	Gemini API with dynamic database context and per-student usage quotas.
Notifications	Custom SMTP-based email templates, OTP, in-app alerts and book availability subscriptions.
Payments	Tenant-specific fine calculation, Stripe and SSLCOMMERZ sandbox checkout and webhook updates.
Infrastructure	Flutter/Dart mobile client; HTML, CSS and JavaScript dashboards; Python/Django REST Framework; MongoDB Atlas free tier (via Djongo); Render deployment and temporary DigitalOcean use.


Project team: Tanjil Hasan, Md. Rashidul Islam, Khadiza-tul Kubra Orin. The project was a collaborative final-year submission; my focus was architecture, mobile and core system development.

Prototype scope: Primarily tested on Android; physical iOS testing and production-scale deployment remain outside the demonstrated scope.
</details>Selected work
<table>
<tr>
<td width="50%" valign="top">
      <img src="assets/projects/audia.png" width="100%" alt="Audia Player — project title artwork" />
      <h3>Audia Player</h3>
      <p><sub>Android app · Public release</sub></p>
      <p>Offline music player with adaptive layouts, media controls and scheduled playback.</p>
      <p><img src="assets/toolkit/kotlin.png" width="70" height="26" alt="Kotlin" /> <img src="assets/toolkit/jetpack-compose.png" width="142" height="26" alt="Jetpack Compose" /> <img src="assets/toolkit/media3.png" width="60" height="26" alt="Media3" /> <img src="assets/toolkit/room.png" width="50" height="26" alt="Room" /></p>
      <p>Kotlin and Compose for the interface, Media3 / ExoPlayer for playback, Room for storage; Android Studio and Gradle for builds.</p>
      <p><b><a href="https://tanjilhasanhimel.me/audia/">View app website</a> &nbsp;·&nbsp; <a href="https://github.com/TanjilHasan-Himel/app">View source code</a> &nbsp;·&nbsp; <a href="https://github.com/TanjilHasan-Himel/app/releases/latest/download/Audia-latest.apk">Download Android APK</a></b></p>
    </td><td width="50%" valign="top">
      <img src="assets/projects/krishi.png" width="100%" alt="Krishi Sheba — project title artwork" />
      <h3>Krishi Sheba</h3>
      <p><sub>Retail SaaS · Prototype</sub></p>
      <p>Agricultural retail operations: inventory, sales, credit and accounting.</p>
      <p><img src="assets/toolkit/next-js.png" width="76" height="26" alt="Next.js" /> <img src="assets/toolkit/postgresql.png" width="106" height="26" alt="PostgreSQL" /></p>
      <p>Next.js for the web interface and PostgreSQL for operational data.</p>
      <p><b><a href="https://khrisisheba-saas-pos.vercel.app/">Live demo</a> &nbsp;·&nbsp; <a href="https://tanjilhasanhimel.me/krishisheba/">Case study</a></b></p>
    </td>
</tr>
<tr>
<td width="50%" valign="top">
      <img src="assets/projects/printdao.png" width="100%" alt="PrintDAO — project title artwork" />
      <h3>PrintDAO</h3>
      <p><sub>Workflow automation · Prototype</sub></p>
      <p>Document upload, payment approval, print queues and desktop printer integration.</p>
      <p><img src="assets/toolkit/next-js.png" width="76" height="26" alt="Next.js" /> <img src="assets/toolkit/supabase.png" width="92" height="26" alt="Supabase" /> <img src="assets/toolkit/python.png" width="78" height="26" alt="Python" /></p>
      <p>Next.js portal, Supabase Realtime and row-level security (RLS), Python / CustomTkinter desktop bridge.</p>
      <p><b><a href="https://printdao.vercel.app/">Open live demo</a> &nbsp;·&nbsp; <a href="https://tanjilhasanhimel.me/printdao/">Read case study</a></b></p>
    </td><td width="50%" valign="top"><h3>Other applications</h3><p><b><a href="https://quarkledger.vercel.app/">Quark Ledger</a></b> — news collection and routing with n8n and webhooks.</p><p><b><a href="https://tdoublehfm.vercel.app/">T Double H FM</a></b> — internet radio and audio delivery.</p><p><b>AI Writing Assistant</b> — PHP, MySQL, cURL and local Ollama integration.</p><p><b>Nirbhor</b> — React, Express.js, MySQL2 and JWT, bcrypt and CORS.</p></td>
</tr>
</table>Embedded systems
<table>
<tr><td width="42%" valign="top"><img src="assets/projects/drone-photos.jpg" width="100%" alt="Original photographs of ESP32 drone development" /></td><td width="58%" valign="top">
<h3>ESP32 Custom Flight Controller</h3>
<p>Academic team project exploring custom flight control rather than a ready-made controller.</p>
<p><img src="assets/toolkit/cpp.png" width="60" height="26" alt="C++" /> <img src="assets/toolkit/esp32.png" width="74" height="26" alt="ESP32" /> <img src="assets/toolkit/arduino.png" width="84" height="26" alt="Arduino" /></p><p><b>Sensor fusion:</b> MPU6050 · Madgwick filter<br/><b>Control:</b> PID · motor mixing · PWM · ESC calibration<br/><b>Communication:</b> UDP / Wi-Fi</p>
</td></tr></table>Product & business perspective
I approach software as a way to improve real workflows: identify the problem, understand users, design the process and translate requirements into a practical solution.
<details>
<summary><b>Requirements, product decisions &amp; business workflows</b></summary>Project	Product / business contribution
SmartLib	Student and library staff requirements, role separation, configurable institutional policies and legacy-system onboarding.
Krishi Sheba	Retail sales, inventory, credit and accounting workflows.
PrintDAO	Upload-to-print journey, payment verification, queue and operator workflows.
Audia Player	Offline listening experience, adaptive layouts and playback convenience.


These are examples of product thinking from my projects, rather than claims of formal analyst or product manager employment.
</details><details>
<summary><b>Planning, documentation &amp; collaboration</b></summary><table>
<tr>
<td width="50%" valign="top"><b>Product planning</b><p>Organizing requirements, tasks and documentation.</p><p><img src="assets/toolkit/notion.png" width="77" height="26" alt="Notion" /> <img src="assets/toolkit/trello.png" width="68" height="26" alt="Trello" /> <img src="assets/toolkit/jira.png" width="55" height="26" alt="Jira" /></p></td><td width="50%" valign="top"><b>Visual &amp; workflow design</b><p>UI design, diagrams and process communication.</p><p><img src="assets/toolkit/figma.png" width="71" height="26" alt="Figma" /> <img src="assets/toolkit/mermaid.png" width="89" height="26" alt="Mermaid" /> <img src="assets/toolkit/draw-io.png" width="80" height="26" alt="draw.io" /></p></td>
</tr>
</table></details>Technology toolkit
Tools I have used or explored across projects and coursework. Each item has one primary home in the toolkit; project-specific stacks above intentionally repeat only where they explain the implementation.
<details>
<summary><b>01 · Programming languages &amp; queries</b></summary><table>
<tr>
<td width="50%" valign="top"><b>Application development</b><p>Web, mobile, backend and academic programming.</p><p><img src="assets/toolkit/python.png" width="78" height="26" alt="Python" /> <img src="assets/toolkit/typescript.png" width="99" height="26" alt="TypeScript" /> <img src="assets/toolkit/javascript.png" width="96" height="26" alt="JavaScript" /> <img src="assets/toolkit/kotlin.png" width="70" height="26" alt="Kotlin" /> <img src="assets/toolkit/dart.png" width="62" height="26" alt="Dart" /> <img src="assets/toolkit/java.png" width="40" height="26" alt="Java" /></p></td><td width="50%" valign="top"><b>Systems &amp; database queries</b><p>Embedded programming, server-side scripting and relational queries.</p><p><img src="assets/toolkit/c.png" width="44" height="26" alt="C" /> <img src="assets/toolkit/cpp.png" width="60" height="26" alt="C++" /> <img src="assets/toolkit/php.png" width="62" height="26" alt="PHP" /> <img src="assets/toolkit/sql.png" width="40" height="26" alt="SQL" /></p></td>
</tr>
</table></details><details>
<summary><b>02 · Web, CMS &amp; mobile development</b></summary><table>
<tr>
<td width="50%" valign="top"><b>Web applications</b><p>Interfaces, dashboards and business systems.</p><p><img src="assets/toolkit/react.png" width="68" height="26" alt="React" /> <img src="assets/toolkit/next-js.png" width="76" height="26" alt="Next.js" /> <img src="assets/toolkit/html.png" width="74" height="26" alt="HTML" /> <img src="assets/toolkit/css.png" width="58" height="26" alt="CSS" /> <img src="assets/toolkit/tailwind-css.png" width="112" height="26" alt="Tailwind CSS" /> <img src="assets/toolkit/shadcn-ui.png" width="94" height="26" alt="shadcn/ui" /> <img src="assets/toolkit/vite.png" width="60" height="26" alt="Vite" /></p></td><td width="50%" valign="top"><b>CMS &amp; websites</b><p>Content-managed websites and local development.</p><p><img src="assets/toolkit/wordpress.png" width="101" height="26" alt="WordPress" /> <img src="assets/toolkit/local-wp.png" width="72" height="26" alt="Local WP" /> <img src="assets/toolkit/xampp.png" width="82" height="26" alt="XAMPP" /></p></td>
</tr>
<tr>
<td width="50%" valign="top"><b>Mobile applications</b><p>Native Android and cross-platform UI.</p><p><img src="assets/toolkit/flutter.png" width="75" height="26" alt="Flutter" /> <img src="assets/toolkit/jetpack-compose.png" width="142" height="26" alt="Jetpack Compose" /> <img src="assets/toolkit/android-studio.png" width="126" height="26" alt="Android Studio" /></p></td><td width="50%" valign="top"><b>Media &amp; local data</b><p>Playback and local application storage.</p><p><img src="assets/toolkit/media3.png" width="60" height="26" alt="Media3" /> <img src="assets/toolkit/exoplayer.png" width="75" height="26" alt="ExoPlayer" /> <img src="assets/toolkit/room.png" width="50" height="26" alt="Room Database" /></p></td>
</tr>
</table></details><details>
<summary><b>03 · Backend, databases &amp; integrations</b></summary><table>
<tr>
<td width="50%" valign="top"><b>Backend &amp; desktop</b><p>REST service logic and desktop utilities.</p><p><img src="assets/toolkit/node-js.png" width="80" height="26" alt="Node.js" /> <img src="assets/toolkit/express-js.png" width="94" height="26" alt="Express.js" /> <img src="assets/toolkit/django.png" width="78" height="26" alt="Django" /> <img src="assets/toolkit/django-rest-framework.png" width="187" height="26" alt="Django REST Framework" /> <img src="assets/toolkit/fastify.png" width="75" height="26" alt="Fastify" /> <img src="assets/toolkit/tkinter.png" width="58" height="26" alt="Tkinter" /> <img src="assets/toolkit/customtkinter.png" width="104" height="26" alt="CustomTkinter" /></p></td><td width="50%" valign="top"><b>Relational data &amp; ORM</b><p>Structured records, local data and database access.</p><p><img src="assets/toolkit/postgresql.png" width="106" height="26" alt="PostgreSQL" /> <img src="assets/toolkit/mysql.png" width="80" height="26" alt="MySQL" /> <img src="assets/toolkit/mysql2.png" width="68" height="26" alt="MySQL2" /> <img src="assets/toolkit/microsoft-sql-server.png" width="146" height="26" alt="Microsoft SQL Server" /> <img src="assets/toolkit/sqlite.png" width="76" height="26" alt="SQLite" /> <img src="assets/toolkit/prisma.png" width="76" height="26" alt="Prisma" /></p></td>
</tr>
<tr>
<td width="50%" valign="top"><b>Document &amp; realtime data</b><p>Flexible documents, caching and backend services.</p><p><img src="assets/toolkit/mongodb.png" width="98" height="26" alt="MongoDB" /> <img src="assets/toolkit/mongodb-atlas.png" width="111" height="26" alt="MongoDB Atlas" /> <img src="assets/toolkit/djongo.png" width="59" height="26" alt="Djongo" /> <img src="assets/toolkit/redis.png" width="67" height="26" alt="Redis" /> <img src="assets/toolkit/supabase.png" width="92" height="26" alt="Supabase" /> <img src="assets/toolkit/firebase.png" width="86" height="26" alt="Firebase" /></p></td><td width="50%" valign="top"><b>Identity &amp; service integration</b><p>Authentication, access policy, communication and payment flows.</p><p><img src="assets/toolkit/rest-apis.png" width="78" height="26" alt="REST APIs" /> <img src="assets/toolkit/jwt.png" width="43" height="26" alt="JWT" /> <img src="assets/toolkit/rbac.png" width="50" height="26" alt="RBAC" /> <img src="assets/toolkit/hmac-sha256.png" width="114" height="26" alt="HMAC-SHA256" /> <img src="assets/toolkit/otp.png" width="42" height="26" alt="OTP" /> <img src="assets/toolkit/smtp.png" width="52" height="26" alt="SMTP" /> <img src="assets/toolkit/bcrypt.png" width="54" height="26" alt="bcrypt" /> <img src="assets/toolkit/cors.png" width="51" height="26" alt="CORS" /> <img src="assets/toolkit/curl.png" width="67" height="26" alt="cURL" /> <img src="assets/toolkit/rls.png" width="38" height="26" alt="RLS" /> <img src="assets/toolkit/stripe.png" width="70" height="26" alt="Stripe" /> <img src="assets/toolkit/sslcommerz.png" width="108" height="26" alt="SSLCOMMERZ" /></p></td>
</tr>
</table></details><details>
<summary><b>04 · Hosting, deployment &amp; engineering workflow</b></summary><table>
<tr>
<td width="50%" valign="top"><b>Hosting &amp; cloud</b><p>Deploying websites and backend services.</p><p><img src="assets/toolkit/vercel.png" width="72" height="26" alt="Vercel" /> <img src="assets/toolkit/netlify.png" width="76" height="26" alt="Netlify" /> <img src="assets/toolkit/render.png" width="78" height="26" alt="Render" /> <img src="assets/toolkit/railway.png" width="82" height="26" alt="Railway" /> <img src="assets/toolkit/digitalocean.png" width="114" height="26" alt="DigitalOcean" /></p></td><td width="50%" valign="top"><b>Infrastructure &amp; delivery</b><p>Deployment environments and domain management.</p><p><img src="assets/toolkit/docker.png" width="78" height="26" alt="Docker" /> <img src="assets/toolkit/linux.png" width="68" height="26" alt="Linux" /> <img src="assets/toolkit/cpanel.png" width="74" height="26" alt="cPanel" /> <img src="assets/toolkit/namecheap.png" width="108" height="26" alt="Namecheap" /> <img src="assets/toolkit/github-actions.png" width="128" height="26" alt="GitHub Actions" /></p></td>
</tr>
<tr>
<td width="50%" valign="top"><b>Development workflow</b><p>Version control, editor and build tools.</p><p><img src="assets/toolkit/git.png" width="52" height="26" alt="Git" /> <img src="assets/toolkit/github.png" width="79" height="26" alt="GitHub" /> <img src="assets/toolkit/vs-code.png" width="67" height="26" alt="VS Code" /> <img src="assets/toolkit/gradle.png" width="74" height="26" alt="Gradle" /> <img src="assets/toolkit/npm.png" width="62" height="26" alt="npm" /> <img src="assets/toolkit/pnpm.png" width="69" height="26" alt="pnpm" /></p></td><td width="50%" valign="top"><b>Testing &amp; API inspection</b><p>Endpoint inspection and software testing.</p><p><img src="assets/toolkit/postman.png" width="88" height="26" alt="Postman" /> <img src="assets/toolkit/rest-client.png" width="86" height="26" alt="REST Client" /> <img src="assets/toolkit/jest.png" width="58" height="26" alt="Jest" /></p></td>
</tr>
</table></details><details>
<summary><b>05 · Embedded systems</b></summary><table>
<tr>
<td width="50%" valign="top"><b>Hardware &amp; communication</b><p>Microcontroller programming and connectivity.</p><p><img src="assets/toolkit/esp32.png" width="74" height="26" alt="ESP32" /> <img src="assets/toolkit/arduino.png" width="84" height="26" alt="Arduino" /> <img src="assets/toolkit/mpu6050.png" width="78" height="26" alt="MPU6050" /> <img src="assets/toolkit/udp.png" width="44" height="26" alt="UDP" /> <img src="assets/toolkit/wi-fi.png" width="48" height="26" alt="Wi-Fi" /></p></td><td width="50%" valign="top"><b>Control &amp; signal processing</b><p>Drone sensor fusion and motor control.</p><p><img src="assets/toolkit/madgwick-filter.png" width="113" height="26" alt="Madgwick Filter" /> <img src="assets/toolkit/pid.png" width="37" height="26" alt="PID" /> <img src="assets/toolkit/pwm.png" width="50" height="26" alt="PWM" /> <img src="assets/toolkit/esc.png" width="39" height="26" alt="ESC" /></p></td>
</tr>
</table></details>Data, analytics & automation
Data exploration, model experimentation and service integration across projects and coursework.
<details>
<summary><b>Data analytics &amp; machine learning</b></summary><table>
<tr>
<td width="50%" valign="top"><b>Data analysis</b><p>Cleaning, exploring and visualizing data.</p><p><img src="assets/toolkit/numpy.png" width="80" height="26" alt="NumPy" /> <img src="assets/toolkit/pandas.png" width="78" height="26" alt="Pandas" /> <img src="assets/toolkit/matplotlib.png" width="78" height="26" alt="Matplotlib" /> <img src="assets/toolkit/microsoft-excel.png" width="109" height="26" alt="Microsoft Excel" /></p></td><td width="50%" valign="top"><b>Machine learning</b><p>Coursework and model experimentation.</p><p><img src="assets/toolkit/scikit-learn.png" width="104" height="26" alt="Scikit-learn" /> <img src="assets/toolkit/pytorch.png" width="82" height="26" alt="PyTorch" /> <img src="assets/toolkit/tensorflow.png" width="105" height="26" alt="TensorFlow" /> <img src="assets/toolkit/jupyter-notebook.png" width="145" height="26" alt="Jupyter Notebook" /> <img src="assets/toolkit/google-colab.png" width="117" height="26" alt="Google Colab" /></p></td>
</tr>
</table></details><details>
<summary><b>Workflow automation &amp; model integration</b></summary><table>
<tr>
<td width="50%" valign="top"><b>Workflow automation</b><p>Connecting services and automating processes.</p><p><img src="assets/toolkit/n8n.png" width="58" height="26" alt="n8n" /> <img src="assets/toolkit/webhooks.png" width="80" height="26" alt="Webhooks" /> <img src="assets/toolkit/mcp.png" width="45" height="26" alt="MCP" /></p></td><td width="50%" valign="top"><b>Model integration</b><p>Hosted and local model APIs.</p><p><img src="assets/toolkit/openai-api.png" width="107" height="26" alt="OpenAI API" /> <img src="assets/toolkit/gemini-api.png" width="103" height="26" alt="Gemini API" /> <img src="assets/toolkit/anthropic-api.png" width="120" height="26" alt="Anthropic API" /> <img src="assets/toolkit/ollama.png" width="78" height="26" alt="Ollama" /> <img src="assets/toolkit/google-ai-studio.png" width="118" height="26" alt="Google AI Studio" /></p></td>
</tr>
</table></details>Development assistants
I use development assistants as supporting tools for prototyping, implementation and reviewing code.
<details>
<summary><b>AI-assisted development tools</b></summary><table>
<tr>
<td width="50%" valign="top"><b>Coding assistants</b><p>Editor and coding workflow assistance.</p><p><img src="assets/toolkit/openai-codex.png" width="124" height="26" alt="OpenAI Codex" /> <img src="assets/toolkit/claude-code.png" width="112" height="26" alt="Claude Code" /> <img src="assets/toolkit/cursor.png" width="56" height="26" alt="Cursor" /> <img src="assets/toolkit/github-copilot.png" width="127" height="26" alt="GitHub Copilot" /></p></td><td width="50%" valign="top"><b>Prototyping tools</b><p>Exploring and iterating on applications.</p><p><img src="assets/toolkit/google-antigravity.png" width="130" height="26" alt="Google Antigravity" /> <img src="assets/toolkit/bolt-new.png" width="69" height="26" alt="Bolt.new" /></p></td>
</tr>
</table></details>Beyond engineering
<table>
<tr>
<td width="50%" valign="top">
<h3>On the air</h3>
<b>Radio Padma 99.2 FM · Presenter / RJ</b>
<p>Live presenting, audience engagement, storytelling and collaboration.</p>
<p><b>Selected shows</b><br/>Hello Rajshahi · Ferari Bikel · Duronto Rajshahi · World Music · Your Request Your Playlist · Bioscope</p>
</td>
<td width="50%" valign="top">
<h3>Creative production</h3>
<p>Audio editing, restoration, video editing and visual storytelling.</p>
<p><img src="assets/toolkit/audacity.png" width="88" height="26" alt="Audacity" /> <img src="assets/toolkit/photoshop.png" width="81" height="26" alt="Photoshop" /> <img src="assets/toolkit/premiere-pro.png" width="94" height="26" alt="Premiere Pro" /> <img src="assets/toolkit/davinci-resolve.png" width="132" height="26" alt="DaVinci Resolve" /></p><p><img src="assets/toolkit/studio-one-6.png" width="95" height="26" alt="Studio One 6" /> <img src="assets/toolkit/izotope-rx.png" width="83" height="26" alt="iZotope RX" /> <img src="assets/toolkit/capcut.png" width="60" height="26" alt="CapCut" /> <img src="assets/toolkit/blackmagic-camera.png" width="154" height="26" alt="Blackmagic Camera" /></p>
</td>
</tr>
</table><div align="center"><a href="https://tanjilhasanhimel.me/">Portfolio and full case studies →</a></div>
