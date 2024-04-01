# ChatGPT-like Chatbot Project

🚀 A fun thing to get hands-on! 🚀
This is a repository for gpt-like clone using OpenAI API and Streamlit
It was a project where I utilized Streamlit and OpenAI’s API (gpt-3.5-turbo), hosted on AWS EC2.

## Challenges Faced

Initially, I attempted to follow this [guide](https://lnkd.in/gDxNdzJP) but encountered some hiccups due to recent updates in the OpenAI API. Additionally, the graphical interface for hosting the chatbot on Gradio wasn't as intuitive as I hoped.

## Solution

After some research, I discovered that Streamlit was the perfect tool for the job, offering a user experience close to ChatGPT! 🎉 It seamlessly generates two characters (user & bot) during conversations and prints the GPT model's responses word-by-word. Check out the [step-by-step tutorial](https://lnkd.in/ghjJQ56a) for more details.

## Hosting

Once the bot was up and running, I faced the challenge of hosting it. While Streamlit offers hosting via GitHub, it poses a security risk as it would expose the private OpenAI API key. To overcome this, I opted to host it on AWS EC2 (which is free tier eligible!). Learn how to set up an [AWS EC2 instance](https://lnkd.in/gvfU4rJA).

## Tips

A little tip here, you would like to use "tmux" or "screen" when you are hosting with `$streamlit run yourbot.py`. This will keep your app running when you disconnect from your AWS instance. Setting up the security settings for the port was crucial to make the link public. Check out the video for the [tutorial setting](https://lnkd.in/guPqBjqR).

## Live Demo

And voilà! The ChatGPT-like chatbot is now live! [Link to the chatbot](http://54.157.52.40:8501)

P.S. If you encounter any errors, it might be due to my dwindling $5 USD OpenAI credit. 😅
