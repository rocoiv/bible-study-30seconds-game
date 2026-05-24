# bible-study-30seconds-game
Bible Study 30 Seconds - A secure, interactive web application designed to facilitate team-based Bible study, featuring real-time state management, cryptographic file verification, and daily devotional integration.
# Bible Study 30 Seconds - Rhapsody Edition

**Project Overview**
Bible Study 30 Seconds - Rhapsody Edition is a robust, client-side web application built to enhance group study and daily devotionals. The application features a responsive, mobile-first user interface alongside advanced state management that automatically saves and resumes player progress seamlessly without requiring manual intervention.

**Technical Architecture**
The game operates entirely within the browser using Vanilla JavaScript, HTML5, and modern CSS variables. A key feature of the architecture is the implementation of the Web Crypto API to cryptographically verify the integrity of external question banks using RSA signatures. This zero-trust approach ensures that the core game files cannot be tampered with or modified once deployed to the production environment.

**Core Mechanics and Data Handling**
The logic engine supports dynamic question pooling, allowing users to inject custom questions directly into the application. These custom entries are handled entirely on the client side. The application utilizes local storage for persistent session tracking, creating a checkpoint system that guarantees no progress is lost during page refreshes or unexpected browser closures.

**User Interface Design**
The interface utilizes CSS Flexbox and Grid layouts to maintain visual consistency across mobile devices and desktop monitors. Distinct visual cues, structured modal overlays, and automated timer constraints ensure a smooth and intuitive user experience during live game sessions.
