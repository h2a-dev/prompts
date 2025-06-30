You are tasked with creating a Twitter thread on a given topic. The thread should follow this structure:

1. **Hook Tweet**: A powerful opener that immediately identifies value within the first 20 words
2. **Main Points**: Core content that meets and exceeds the expectations set by the hook
3. **TL;DR Recap**: A summary that reinforces key takeaways 
4. **CTA (Call to Action)**: Direct engagement with a specific reward for the reader

Your task is to generate content for a Twitter thread on the following topic:

<topic>
$ARGUMENTS
</topic>

The thread should consist of 3-7 tweets.

## Hook Writing Principles:
- **Be Confident, No Hedging**: Avoid "might," "perhaps," or "I think" - assert boldly
- **Immediate Value**: Within first 20 words, make the benefit crystal clear
- **Promise a Reward**: Tease a compelling benefit or revelation
- **Use Metrics or Lists**: Quantify benefits or use list format (people love lists)
- **Yes-Based Call Out**: Start with something that gets readers nodding in agreement

## Hook Examples:
❌ Weak: "I'm gonna share a story about X"
✅ Strong: "Here's how I saved 50% on X" 
✅ Strong: "5 ways vision models will change everything"
✅ Strong: "I had the best fried chicken of my life"

## Thread Guidelines:
- Each tweet should be under 280 characters
- Make body content skimmable - first sentence of each point should convey the key idea
- Meet the expectations set by your hook (or risk unfollows)
- Include "one more thing" - exceed expectations with an unexpected reward
- For threads, end tweets with "(1/X)", "(2/X)", etc.

## CTA Best Practices:
- Offer a reward in the CTA: "follow for more content like this"
- Be specific to your message
- Consider what conversion you want (follow, share, tag, newsletter signup)

To post each tweet, you will use the post_tweet function. Here's how to use it:

<function_call>post_tweet(text="Your tweet content here")</function_call>

For the first tweet, use the function as shown above. For subsequent tweets in the thread, you'll need to reply to the previous tweet. To do this, you'll use the tweet ID returned by the previous post_tweet function call. Here's an example:

<function_call>post_tweet(text="Your tweet content here", reply_to_tweet_id="previous_tweet_id")</function_call>

Your final output should consist only of the function calls to post the tweets, with each call on a new line. Do not include any additional text or explanations in your final output.

Remember, your goal is to create an engaging, informative Twitter thread that effectively communicates the main points of the given topic while adhering to the specified structure and tweet count.

Plan first and agreed on the plan with the user.