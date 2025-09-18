# Audiveris in Gitpod

This repo lets you run **Audiveris** (open-source Optical Music Recognition) directly in your browser using [Gitpod](https://gitpod.io).

---

## How to use

1. **Upload these files to a new GitHub repository** (e.g., `audiveris-cloud`).

2. **Open your repo in Gitpod**  
   Replace `<your-repo>` with your GitHub URL:  
   ```
   https://gitpod.io/#https://github.com/<your-username>/<your-repo>
   ```

   Example:  
   ```
   https://gitpod.io/#https://github.com/janedoe/audiveris-cloud
   ```

3. **Wait for the Gitpod workspace to build.**  
   - It will download Audiveris automatically.  
   - A browser-based desktop (VNC) will appear.  

4. **Start Audiveris**  
   In the terminal, run:  
   ```bash
   bash /workspace/audiveris/bin/audiveris.sh
   ```

5. **Convert your PDF**  
   - In the Audiveris GUI: **File → Open** → choose your PDF.  
   - Then: **File → Export → MusicXML** to save.  

---

## Notes
- Works best with **printed, clean scores**. Handwritten or fuzzy scans may need lots of correction.
- The workspace is temporary; if you want to keep MusicXML files, download them before closing Gitpod.
