
Bubble City Design Proposal 2.0

Monica Anderson 

Follow Popular Messages 
More like this impacts my own stream but it may also be used by the system as a hint about message 
importance. If many users click on More Like This or Follow a Thread of some message, then that 
message can be showed to users that want to see popular messages. We will not use popularity for 
filtering messages unless necessary, because popularity can be exploited by malicious users to improve 
reach. Follow New Messages 
Follow the raw incoming message stream. This is more than any human can read so we still need to apply 
some filtering to the stream. The default filtering is to randomly discard enough messages so that a user 
can read what remains by using the Pacer. 
Follow Trusted Streams 
Messages may come not only from other users but from well known named message streams such as 
Reuters. Historically, these have not been subject to additional filtering but if we use Message Routing By 
Content then there is no reason to not filter those using the same filters we apply to messages from other 
users. Follow Friends And Family 
Social media are different from chat applications because of the emphasis on people and the use of some 
kind of friendship graph that is used mainly for message routing. 
This has proven itself historically as very popular but I would like to focus on a Service that supports 
group problem solving rather than social interactions. Implementing a social graph brings along a lot of 
complexity and will be much more expensive to create and maintain than routing messages, and it may 
become a problem if we wish to (at least ideologically, if not legally) attain Common Carrier status. 
The minimum level, where you can create Bubbles containing all messages from specific individuals and 
we do not maintain a social graph, is cheap and acceptable as an add-on for marketing reasons. 
ClickBait Headlines Completely Eliminated 
We can totally avoid clickbait headlines. I reserve disclosure of this mechanism to NDA level discussions. 
This solution also simplifies or solves several other problems in Service design and implementation. 
Traf f ic Logging for Machine Learning 
All posts are public. All posts need to be kept for at least some time in a repository so that they can be 
displayed to others as required, but this is designed to be a real-time system so we may impose limits on 
history length. 
Because everything is public, users have no expectation of privacy for this content. We will use messages 
in our message repository as a corpus for training future versions of the system. We will not sell these 
corpora to outsiders but may share them with (corporate) collaborators for language research and product 
enhancement purposes. 
Bubble City Design Proposal 2.0 of 
910Monica Anderson 
No Voting On Messages 
SlashDot and Reddit use voting. This should be unnecessary and is mostly a nerd-favored solution to 
noise problems. No Need for #HashTags 
#HashTags were invented by both IRC and Twitter users in response to the service lacking a decent 
semantic search capability. 
We cannot prevent users from using these features but we can decide whether we want to explicitly 
support tagging by (for instance) providing a tag canonicalizing service. 
IRC and Twitter users use this Edit Button 
This seems important to some people, but editing would change the Bubble definition and this causes 
trouble in many places. This is definitively not going to be in the first release. 
No Subscription fees 
This substantially lowers the threshold for joining. 
No Advertising

Pacer 
Message streams may be very voluminous. No human can read all posted messages, and cannot even read 
all Popular messages or all messages in their stream if they have many Bubbles. Social Media will have to 
prioritize messages and discard those that have poor engagement. 
It would be an awful user experience if messages just scroll away before we can read them. The Pacer is 
essentially a speed control that indicates how many messages the user wishes to see per minute. It starts at 
something like ten messages per minute which means a new message every six seconds and can be tuned 
up and down. 
Which messages are shown when 99.99% are discarded? We can attempt to show the most popular 
messages or the messages that best match our more-or-fewer filters. But the simplest implementation is to 
pick messages from the stream at random to fulfill the view rate set by the user. 
This means that a convenient way to enjoy an app like this is to open the front page and just read 
whatever is scrolling by at your set speed – whatever you can keep up with. It will be like watching 
television, if you do not intend to interact. 
But if you see an interesting post slowly scrolling up the screen then you can just click on it to see that 
message, in its thread, in a new "Thread View" window or tab 
This feels to me like a very comfortable and coherent user interface design. 
The two selection directions can optionally be used to indicate dif f erent purposes for the selected text 
1 Bubble City Design Proposal 2.0 of 
710Monica Anderson 
Sample User Experience 
Here is an example of what the user experience might look like. 
Suppose you want to follow an ongoing sports event, like some World Cup. 
Use the Search Feature: Enter [world cup] in the search box and hit return. A new window (or tab, 
depending on your preferences) opens. You have created a "Bubble", and it is displayed in a "Bubble 
Window". In this mode, Bubble City is used a bit like a web search engine like Google or Bing, but it is 
designed to be used for real time messages. The result of a search on Bubble City is a topic specific chat 
room (just one, not a list of results as in web search) where people only discuss the topic you searched for. 
No matter what it is. 
All bubbles open in a new window (or tab). This one will have messages about the World Cup, going 
back as far in time as you have screen height for, and can be scrolled. 
You can read these messages to catch up. In low-traffic bubbles there may not be many at all, and some 
messages may be quite old. Messages you have already seen will be displayed in gray. You can scroll 
back in higher-volume bubbles. Or just mark everything as read. 
Sample User Experience : Swipe Tuning 
You start by browsing message titles in the Bubble View. You swipe left on those that are irrelevant to 
you, or possibly spam, and they turn a reddish gray, but stay around for now. There may be "collateral 
rejection" of other messages on the same topic also turning reddish gray. You swipe right on the best stuff 
and such messages (and associated messages on same topic) may get a green highlight. There is a button 
for refresh, that redraws the screen, discarding everything that was labeled as irrelevant, and accepting the 
green highlights, which may mean other messages similar to the ones you have right-swiped may appear. 
If you are on some device that cannot use swipe then you can use buttons labeled- (Minus) and + (Plus) 
on each message to deprecate or encourage that message, and any similar messages. 
You can now click on any message that looks extra interesting. Another window/tab opens and in there, 
this message will be in the center. Above it, in reverse chronological order, you see older messages being 
added in reverse time sequence going upward (towards older messages) and if there is traffic in the 
bubble, you will see the new messages in the thread for the bubble of the clicked message appear below 
the initial message. 
If you do not swipe-tune, then this bubble will stay true to the spirit of the original message you clicked 
on, but you can swipe-tune any message in any display at any time, and your swipe-tunes will become 
permanently part of your Bubble definition when you close and save the Bubble. 
Also, when you have opened a Thread view on some single message and its thread, you can immediately 
reply to the message you clicked on. This is the most common way to post something. Click on something 
interesting, see its thread, type a reply, and then stay around watching the thread continue after your own 
message. 
To get a topic started, create (enter) a Bubble. If there is no traffic in the Bubble, just post something and 
others may reply. They may have entered the same Bubble weeks ago.


ClickBait Headlines Completely Eliminated 
We can totally avoid clickbait headlines. I reserve disclosure of this mechanism to NDA level discussions. 
This solution also simplifies or solves several other problems in Service design and implementation. 
Traf f ic Logging for Machine Learning 
All posts are public. All posts need to be kept for at least some time in a repository so that they can be 
displayed to others as required, but this is designed to be a real-time system so we may impose limits on 
history length. 
Because everything is public, users have no expectation of privacy for this content. We will use messages 
in our message repository as a corpus for training future versions of the system. We will not sell these 
corpora to outsiders but may share them with (corporate) collaborators for language research and product 
enhancement purposes. 
Bubble City Design Proposal 2.0 of 
910Monica Anderson 
No Voting On Messages 
SlashDot and Reddit use voting. This should be unnecessary and is mostly a nerd-favored solution to 
noise problems. No Need for #HashTags 
#HashTags were invented by both IRC and Twitter users in response to the service lacking a decent 
semantic search capability. 
We cannot prevent users from using these features but we can decide whether we want to explicitly 
support tagging by (for instance) providing a tag canonicalizing service. 
IRC and Twitter users use this Edit Button 
This seems important to some people, but editing would change the Bubble definition and this causes 
trouble in many places. This is definitively not going to be in the first release. 
No Subscription fees 
This substantially lowers the threshold for joining. 
No Advertising 
This would substantially lower the enjoyment of the system.We want to monetize this service exclusively 
by selling postage. Links 
Monica's Patents assigned to Google. 
Introduction to AI Epistemology 
Videos of Talks

Bubble City 
Design Proposal 
A Twitter Alternative 
Which is not a Social Medium 
It is a 
Real Time Idea Router 
Monica Anderson 
Syntience Inc 
October 31, 2022


https://syntience.com/BubbleCity2.pdf


https://jimruttshow.blubrry.net/the-jim-rutt-show-transcripts/currents-086-monica-anderson-on-bubble-city/



# AI Bootcamp

The "Get Shit Done with AI" Bootcamp focuses on real-world applications that will equip you with the skills and knowledge to become a great AI engineer

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/curiousily/AI-Bootcamp/)
[![](https://dcbadge.vercel.app/api/server/UaNPxVD6tv?style=flat)](https://discord.gg/UaNPxVD6tv)
[![](https://img.shields.io/youtube/channel/subscribers/UCoW_WzQNJVAjxo4osNAxd_g?label=Watch%20on%20YouTube)](https://bit.ly/venelin-subscribe)
[![](https://img.shields.io/github/license/curiousily/AI-Bootcamp)](https://github.com/curiousily/AI-Bootcamp/blob/master/LICENSE)

## 🍿 Watch on YouTube

- [Real-World PyTorch](https://www.youtube.com/watch?v=dgs_9quxZXk)
- [Build Real-World Machine Learning Project](https://www.youtube.com/watch?v=ug1FA7qzWSc)
- [Fine-tuning Tiny LLM on Your Data](https://www.youtube.com/watch?v=_KPEoCSKHcU)
- [Deploy (Tiny) LLM to Production](https://www.youtube.com/watch?v=c10rsQkczu0)
- [AI Agents with GPT-4 Turbo and CrewAI](https://www.youtube.com/watch?v=Ev0uzdzesjU)
- [CrewAI with Open LLM (Llama 3) using Groq API](https://www.youtube.com/watch?v=N5sos1X30Rw)
- [Fine-Tuning Llama 3 on a Custom Dataset](https://www.youtube.com/watch?v=0XPZlR3_GgI)
- [Local RAG with Llama 3.1 for PDFs](https://www.youtube.com/watch?v=ofNbLa2-5SU)

## 📖 Read the Tutorials

### Foundational Skills

- [Python Essentials for AI: A Practical Guide](https://www.mlexpert.io/bootcamp)
- [Real-World PyTorch](https://www.mlexpert.io/bootcamp/real-world-pytorch)

### ML Pipelines

- [Analyze Data For Insights](https://www.mlexpert.io/bootcamp/analyze-data-for-insights)
- [Develop Your Model](https://www.mlexpert.io/bootcamp/develop-your-model)
- [Evaluate Your Model](https://www.mlexpert.io/bootcamp/evaluate-your-model)
- [Architect Your ML Project](https://www.mlexpert.io/bootcamp/architect-your-ml-project)

### Large Language Models (LLMs)

- [LLMs 101](https://www.mlexpert.io/bootcamp/llms-101)
- [Write Great Prompts](https://www.mlexpert.io/bootcamp/write-great-prompts)
- [Build a RAG System](https://www.mlexpert.io/bootcamp/build-a-rag-system)
- [Fine-tuning Tiny LLM on Custom Dataset](https://www.mlexpert.io/bootcamp/fine-tuning-tiny-llm-on-custom-dataset)
- [Deploy Custom LLM to Production](https://www.mlexpert.io/bootcamp/deploy-custom-llm-to-production)
- [LLM Evaluation](https://www.mlexpert.io/bootcamp/llm-evaluation)

### AI Agents

- [Build Agentic Apps](https://www.mlexpert.io/bootcamp/build-agentic-apps)
- [Agents with Llama 3 and Custom Tools](https://www.mlexpert.io/bootcamp/agents-with-llama-3-and-custom-tools)
- [Develop a Tweet Writing Team](https://www.mlexpert.io/bootcamp/ai-agents-in-action)
- [SQL Agents with CrewAI and Llama 3](https://www.mlexpert.io/bootcamp/sql-agents-with-crewai)

### Projects

- [RagBase - Private Chat with Your Documents](https://www.mlexpert.io/bootcamp/ragbase-local-rag)
- [Write Social Media Content with Agents](https://www.mlexpert.io/bootcamp/write-social-media-content-with-agents)
