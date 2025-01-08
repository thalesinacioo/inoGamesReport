# Hands-On Test (InoGames)

## ■ Big Bass Floats My Boat

I read the rules in the page, and I was Playing normally when I noticed something weird, and I tried to reproduce following the rules founded in the page.
So I can't calculate correctly to get the same result's that I found on the game, well, so I need to think out of the box, I can get some help here, I explain all the rules to Gemini, and ask to gemini about the results following the rules and here what I found:
        
My Prompt: 
```
Credits: 100,000.00 Bet value: 250.00 I played 5 times Appear 2 scatter icons at screen side by side, following the rules this won something? Appear 2 icons of fish, 1 icon value 50.00 the other one is down position, value: 125.00 But I don't know if I won something.
```

Gemini answer:
```
Okay, let's break down this scenario:

Information:

Starting Credits: 100,000.00
Bet Value: 250.00 per spin
Number of Spins: 5
Scatter Icons: 2 (appeared side by side)
Fish Icons: 2 (one 50.00, one 125.00)

Calculations:

Total Bet Amount: 250.00 * 5 = 1,250.00

Credits Remaining After Spins (Before Wins): 100,000.00 - 1,250.00 = 98,750.00

Fish Icon Winnings (with multiplier):

Fish 1: 50.00 * 1 = 50.00

Fish 2: 125.00 * 2 = 250.00

Total Fish Winnings: 50.00 + 250.00 = 300.00

Total Winnings: 300.00 (from fish icons)

Final Credits: 98,750.00 + 300.00 = 99,050.00

```
![Screenshot_4](https://github.com/user-attachments/assets/6b35c236-2024-49f2-986f-3c444b5483ba)

But the result's in my game was only 98,750.00. So I don't know if I miss something in the rules or really need to investigate if I found a BUG.
Based on that, I opened a bug ticket that you can see here: 

![screencapture-thalesinacioo-atlassian-net-browse-DP-7-2025-01-08-10_50_19](https://github.com/user-attachments/assets/878e5417-e22b-4c39-833b-8a4578de773f)

## Functional Testing and performance:

**Verify that the game loads properly on different browsers (Chrome, Firefox, Safari, Edge).**

**Chrome:** 

I noticed some licks at loading, but my computer has 10 years. So is hard to evaluate that.

Page load take 7.2s FPS: normally at 59.6fps maximum at my computer

**Firefox:** 

I noticed some licks at same part of Chrome.

Page load take 2.60s. FPS: normally at 59.6fps maximum at my computer

**Edge:**

I noticed some licks at same part of Chrome.

Page load take 2.8s. FPS: normally at 54.6s

**Safari: Not available for windows anymore.**

**Check that all buttons and controls (e.g., spin, bet, autoplay) function as expected.**

All the game buttons are working normally, but in settings, has one in gray that I didn't have how to acces: Game history button in grey.

Ensure that animations and graphics display correctly without glitches.

I notice some licks, but only in my computer, other peripherics didn't show the glitches.

Specs: i5 (2014), 4gb ram, Windows 10 pro.

# Usability Testing:

**Evaluate the game’s user interface for ease of use.**

I think the interface is easy to use, but the usability is not all good, I will purpose a option on settings to activate names in buttons, some buttons doesn't have names, probably it is good to add a description in all of them, not only in autoplay. If the user using money and doesn't know what a button does, probably he feels afraid to click. But this needs more understand of the rules and approach of the company.

**Test the games responsiveness on different screen sizes (desktop, tablet, mobile).**

I Found a bug here and I opened a issue on Jira:

![screencapture-thalesinacioo-atlassian-net-browse-DP-8-2025-01-08-11_35_16](https://github.com/user-attachments/assets/7acdd1f1-1e73-49a1-834b-0fc8ab12d4f3)

Why I choose this game? weel, I noticed in the email that has a letter T missing on the link and I had a 404 error in the first acces, so I think, hmm, this is a good trick to start.
I like the colors and I like to play, but I miss more animations in the lines like on the Esqueleto Explosivo 2.
It was an engaging experience, but I think if we had more animations it will be more addict.


