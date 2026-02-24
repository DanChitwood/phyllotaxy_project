# Phyllotaxy Data Collection Project 🌵

This repository contains the interactive tool for collecting parastichy data from plant images.

### 🚀 How to use the tool
No installation is required. You can run the tool directly in your browser via Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DanChitwood/phyllotaxy_project/blob/main/PHYLLOTAXY_DATA.ipynb)

1. Click the **Open in Colab** button above.
2. Sign in with your Google Account.
3. Select **Runtime** > **Run all** from the top menu, or click the Play button (▶) on the code cell.
4. Scroll down to the bottom of the page to enter your info and upload your image.

---

### 🎥 Video Tutorial
If this is your first time using the tool, we highly recommend watching the video tutorial below:

[![Phyllotaxy Project Tutorial](https://img.youtube.com/vi/jUSZy3QBZsk/0.jpg)](https://www.youtube.com/watch?v=jUSZy3QBZsk)  
*Click the image above to watch the tutorial on YouTube.*

---

# Parastichy Data Collection Instructions 🌀

Follow these steps to trace the spiral patterns (parastichies) on your plant image.

**Before you start:** Click the **Play button (▶)** on the left side of the code cell below. Then, scroll to the bottom of the cell to interact with the tool.

---

1. **Upload & Info:**
   - **Upload your image:** Click the upload button. `.jpg` or `.png` are preferred, but most formats work.
   - **Enter your details:** Provide your **Full Name** (for publication credit), **Institution** (or `none`), **Location** (e.g., "El Charco botanical garden" or "UNAM Jardín Botánico), and a valid **Email Address**.
   - Click **START TRACING** to load your image.

2. **Tracing Family A:**
   - Click points along a single spiral "arm," moving from the **center to the periphery**. Try to click every sequential node (areole/tubercle, leaf, etc) you can identify.
   - When one arm is finished, click **NEXT ARM**.
   - Trace **every arm** visible in that specific direction.
   - **The Guardrail:** The total number of arms in this family must be a Fibonacci number (e.g., `5`, `8`, `13`, `21`, `34`, etc.). If the count is incorrect, the tool will alert you.
   - When finished with the first set, click **FINISH FAMILY A**.

3. **Tracing Family B:**
   - You will now see your first family in **black**. Trace the arms spiraling in the **opposite direction**.
   - **Tip:** When a point in Family B crosses a black point from Family A, click as close to the black point as possible. This helps us consolidate the data.
   - Click **NEXT ARM** after each arm, and **FINISH & DOWNLOAD ZIP** when the entire second family is complete.
   - **The Guardrail:** Family B must be the Fibonacci number immediately adjacent to Family A (e.g., if Family A was `13`, Family B must be `8` or `21`).

4. **Your Downloaded Results:**
   The tool will automatically download a `.zip` file named after your image. Inside you will find:
   - 🖼️ **The original image** and a **plotted version** (`_parastichies`) showing your work.
   - 📊 **Results CSV:** A data file containing every coordinate you clicked.
   - 📝 **Info CSV:** A file containing your authorship and location information.

**Final Step:** Please deposit your `.zip` file or email it to the project lead as instructed. Your contribution is vital to our collective analysis!

--- 
### Phyllotaxy Lecture

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DanChitwood/phyllotaxy_project/blob/main/PHYLLOTAXY_LECTURE.ipynb)

To follow along with code during the lecture, click the **Open in Colab** button above. Or, you can simply follow the lecture using the Jupyter notebook in this GitHub repo [here](https://github.com/DanChitwood/phyllotaxy_project/blob/main/PHYLLOTAXY_LECTURE.ipynb).
