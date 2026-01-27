# Data Privacy & Confidentiality Reflection
**Author:** Rahul Adithya

## 🔍 Research & Learn

### 1. Key Takeaways from Focus Bear’s Privacy Policy
Focus Bear is committed to protecting user data through a "Privacy by Design" approach. Key takeaways include:
* **Purpose Limitation:** Data is only collected to provide and improve the focus and habit-tracking services.
* **User Control:** Users have the right to access, export, or delete their personal information at any time.
* **Minimalism:** The app aims to collect the least amount of data necessary for functionality.

### 2. Types of Confidential Data at Focus Bear
At Focus Bear, confidential data includes:
* **User Data:** Personal habits, focus session history, and email addresses.
* **Company Information:** Proprietary source code, internal roadmap documents, and API keys.
* **Employee/Intern Data:** Personal contact information and internal performance reviews.

### 3. Best Practices for Handling Confidential Data
* **Need-to-Know Basis:** Only access data that is strictly required for your current task.
* **Encrypted Sharing:** Never share passwords or tokens in plain text; use secure vaults or encrypted channels.
* **Anonymization:** When testing or debugging, use dummy data instead of real user information.

### 4. Responding to a Suspected Data Breach
If a breach or accidental disclosure is suspected, the following steps must be taken immediately:
1. **Report:** Notify your supervisor or the security lead at Focus Bear without delay.
2. **Contain:** Stop the activity that caused the leak (e.g., delete a public gist containing a token).
3. **Audit:** Document exactly what information was exposed and when.

---

## 📝 Reflection

### Steps for Daily Data Security
In my daily tasks, I will ensure that my local development environment is secure by using full-disk encryption and avoiding the storage of sensitive company data in unencrypted local folders. I will also verify the destination of every file I upload to GitHub to ensure no internal credentials are included.

### Safe Storage, Sharing, and Disposal
* **Storage:** I will store all work-related credentials in a password manager rather than local text files.
* **Sharing:** I will use the "Secret" feature on GitHub for environment variables instead of hardcoding them into scripts.
* **Disposal:** I will securely delete temporary local files or logs that contain sensitive information once a task is completed.

### Common Mistakes & Avoidance
A common mistake is accidentally committing secrets (like `GITHUB_TOKEN`) to public repositories. I can avoid this by using `.gitignore` files consistently and performing a manual "diff" check before every commit to review exactly what code is being pushed.

---

## 🛠️ Task Completion

### Adopted Security Practice
**Habit:** I will implement a **Pre-Commit Security Audit**. 
**Detail:** Before every `git push`, I will manually review my changes for any hardcoded strings, tokens, or internal paths that should remain private.

### Key Learning / Security Measure
**Measure:** Implementing "Environment Variable Isolation."
**Learning:** I have learned that sensitive configurations should never reside in the main code. I will always use a `.env` file that is explicitly listed in `.gitignore` to prevent accidental data leaks.
