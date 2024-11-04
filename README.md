# Asymptotic Cuteness: The Infinite Cat Optimization Loop

Welcome to **Asymptotic Cuteness**, an innovative project developed during the [lablab.ai](https://lablab.ai/) hackathon using the [rhymes.ai](https://rhymes.ai) platform. This project explores the synergy between advanced AI models—**Aria** and **Allegro**—to iteratively enhance the cuteness of cat videos, approaching the asymptote of ultimate adorableness.

## Table of Contents

- [Introduction](#introduction)
- [Project Goal](#project-goal)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Potential Applications](#potential-applications)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

**Asymptotic Cuteness** leverages cutting-edge AI technologies to create a self-improving system that enhances the appeal of cat videos through iterative optimization. By combining **Aria**, a multimodal large language model, and **Allegro**, an advanced generative video model, we demonstrate how AI can approach ideal outcomes through continuous refinement.

## Project Goal

The primary objective is to generate a video of a cute cat and make it progressively cuter with each iteration. By forming an optimization loop, we aim to approach the asymptote of ultimate cuteness—acknowledging that while perfection may be unattainable, continuous improvement can bring us infinitely close.

## How It Works

The project follows a systematic process:

1. **Generate Initial Video**: Use **Allegro** to create a video from a textual prompt (e.g., "a cute cat wearing glasses, sitting at a laptop with code on the screen").

2. **Analyze Video with Aria**: **Aria** evaluates the video's cuteness, providing a rating and suggestions for enhancement.

3. **Enhance Key Frames**: Extract key frames from the video and enhance them using **Aria**, focusing on features that increase appeal.

4. **Generate New Video**: Feed the enhanced images back into **Allegro** to create a new, improved video.

5. **Iterative Optimization**: Repeat the process, with each iteration aiming to produce a cuter video than the last.

This loop mirrors reinforcement learning principles:

- **State**: The current version of the video.
- **Action**: Enhancing images and regenerating the video.
- **Reward**: The cuteness rating provided by **Aria**.

## Technologies Used

- **[Aria](https://rhymes.ai/aria)**: A multimodal large language model capable of understanding and processing both text and images.
- **[Allegro](https://rhymes.ai/allegro)**: An advanced generative model that creates videos from textual prompts.
- **Python**: For scripting and automation of the optimization loop.
- **GitHub**: Version control and collaboration.
- **Markdown**: Documentation and presentation.

## Usage

**Note**: Access to **Aria** and **Allegro** models is required.

1. **Clone the Repository**

   ```bash
   git clone https://github.com/sness23/infinitepurrfection.git
   ```

2. **Install Dependencies**

   Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up API Access**

   Ensure you have API keys or access tokens for **Aria** and **Allegro**. Set them as environment variables.

   ```bash
   export ARIA_API_KEY="your_aria_api_key"
   export ALLEGRO_API_KEY="your_allegro_api_key"

4. **Edit the prompt**

   Edit the prompt.txt file to set your prompt to your liking.

5. **Run the Optimization Loop** 
   Execute the main script to start the iterative process:

   ```bash
   make
   ```

6. **View Results**

   The generated videos and enhanced images will be saved in the current directory for each iteration.

## Project Structure

```
asymptotic-cuteness/
├── README.md
├── Makefile
├── catception_generate_video.py
├── catception_get_video.py
├── catception_analyze_video.py
├── catception_new_prompt.py
├── prompt.txt
├── requirements.txt
└── LICENSE
```

- **catception_generate_video.py**: Generate cat video with Allegro
- **catception_get_video.py**: Get the URL of the generated video with Allegro
- **catception_analyze_video.py**: Analyze cat video with Aria
- **catception_new_prompt.py**: Generate new prompt with Aria
- **output/**: Directory where outputs of each iteration are stored.

## Results

Through iterative optimization, the project achieves significant enhancements in the video's appeal:

- **Visual Improvements**: The cat's features become more expressive, colors are more vibrant, and the background is more engaging.
- **Cuteness Rating**: Incremental increases in the cuteness rating with each iteration, approaching the asymptote of ultimate cuteness.

## Example Progression


### Iteration 0
Both images feature an adorable cat wearing a party hat, sitting beside a cupcake with a candle, creating a delightful and festive scene. Here’s a detailed evaluation:

1. **Cuteness**: 
   - **Image 1**: 80/100 
   - **Image 2**: 82/100 

2. **Engagement**: 
   - **Image 1**: 81/100 
   - **Image 2**: 84/100 

3. **Visual Distortions**: 
   - Both images are free from any noticeable visual distortions.

**Summary**: Both images score high in cuteness and engagement, with Image 2 slightly outperforming due to its sharper focus and vibrant colors. Each image is an excellent representation of the prompt.

---

### Iteration 1
Both images showcase a charming cat adorned with a party hat, sitting next to a cupcake with a lit candle, successfully capturing a playful spirit. 

- **Image 1**: Scores 89/100 
   - The cat's curious expression and festive hat contribute to the overall charm. High quality with vibrant colors and excellent lighting enhances the appeal.

- **Image 2**: Scores 85/100 
   - This image, while engaging, features a less dynamic expression from the cat and is slightly less sharp. 

**Visual Quality**: Both images boast high quality, showing no visual distortions.

---

### Iteration 2
The images present a delightful scene filled with cuteness and engagement. The cat's playful expression, combined with a colorful party hat, brings joy to viewers. 

- **Cuteness & Engagement**: Both images score 90/100
- The effective lighting adds warmth, creating an inviting atmosphere.

**Visual Quality**: No visual distortions are present, making both images appealing representations of a joyful moment.

---

### Iteration 3
These images are exceptionally engaging and adorable. Here’s a refined assessment:

1. **Cuteness**: 
   - **Image 1**: 90/100 
     - The playful element is highlighted by the cat's expression and party hat.
   - **Image 2**: 92/100 
     - The cat’s blinking enhances its charm, making it even cuter.

2. **Engagement**: 
   - **Image 1**: 92/100 
     - Strong composition keeps the viewer's attention.
   - **Image 2**: 93/100 
     - The dynamic action of the cat blinking and waving increases engagement.

3. **Visual Distortions**: 
   - Both images are clear and free of any noticeable distortions.

**Conclusion**: Image 2 edges slightly higher due to the added motion and expression of the cat, making it feel more alive and engaging.


## Potential Applications

While this project focuses on enhancing cat videos, the methodology can be applied to various fields:

- **Marketing**: Iteratively enhancing advertisements to maximize consumer engagement.
- **Entertainment**: Refining animations or CGI elements for greater audience appeal.
- **Design**: Continuously improving product images for higher aesthetic value.

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the Repository**

2. **Create a Feature Branch**

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Commit Your Changes**

   ```bash
   git commit -m "Add your message here"
   ```

4. **Push to the Branch**

   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a Pull Request**

## License

This project is licensed under the **GPL v3**. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **lablab.ai**: For hosting the hackathon and providing a platform for innovation.
- **rhymes.ai**: For developing the **Aria** and **Allegro** models.
- **丹丹**: For the creative "hacker cat" and "cute cat in a kitchen making its favorite meal" prompt idea.
- **小白**: For inspiration and support

---

Feel free to explore, contribute, and reach out with any questions or suggestions. Together, let's push the boundaries of AI-driven content optimization!
