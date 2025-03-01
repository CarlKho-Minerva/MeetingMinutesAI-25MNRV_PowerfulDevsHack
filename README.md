# Project Title: AI-Powered Meeting Minutes & Gift Generator

## Hackathon Category: Best in Automation, Best in AI, Best in Applications, Best in Power

<div>
    <a href="https://www.loom.com/share/bea858f72cc8442d906e5f1fe6cad9b6">
      <p>The Efficient Santa Clause | MS PowerDevs Hackathon - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/bea858f72cc8442d906e5f1fe6cad9b6">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/bea858f72cc8442d906e5f1fe6cad9b6-8843f5152316e9be-full-play.gif">
    </a>
  </div>

## Project Description:

The AI-Powered Meeting Minutes & Gift Generator is a Power Platform solution designed to revolutionize meeting follow-up and foster a more human-centered workplace. It leverages AI to analyze meeting transcripts, automatically generate structured meeting minutes in HTML format, and uniquely, suggest thoughtful and personalized gift ideas for action item owners.  By subtly incorporating elements of employee recognition inspired by watercooler conversations, this solution aims to improve employee retention and satisfaction through seamless, AI-driven empathy at scale. The system operates as a fully automated email flow, requiring no additional user interface for PMs or HR.

<img width="629" alt="image" src="https://github.com/user-attachments/assets/d9e54c0a-d371-4247-a6f3-979803f6d0fb" />
<img width="436" alt="image" src="https://github.com/user-attachments/assets/f97503be-0111-495d-aaa8-422fc7f38eff" />
<img width="574" alt="image" src="https://github.com/user-attachments/assets/19378639-0b85-48ac-8361-f8ade35355a6" />


## Setup and Testing Instructions:

To test this project, please follow these steps after importing the solution:

1.  **Import the Solution Package:**
    *   Download the `Meeting Minutes Gift Generator 1.0.0.zip` file from this GitHub repository.
    *   Go to the Power Apps Maker Portal: [https://make.powerapps.com/](https://make.powerapps.com/)
    *   Ensure you are in a Power Platform environment where you have solution import permissions.
    *   Navigate to "Solutions".
    *   Click "Import solution".
    *   Browse and select the downloaded `.zip` file.
    *   Click "Next" and then "Import". Wait for the solution import to complete successfully.

2.  **Open and Test the Power Automate Flow:**
    *   After import, open the "Solutions" list and find the "MeetingMinutesGiftGeneratorHack" solution.
    *   Open the solution.
    *   Locate and open the Power Automate flow named "Generate Meeting Minutes and Gifts" in edit mode.
    *   Click "Test" -> "Manually" -> "Test".
    *   In the "Meeting Transcript" input, paste the sample meeting transcript provided below (or use your own meeting transcript).
    *   Click "Run flow".
    *   Approve the "Approval Request" email sent to you.
    *   Check your email inbox (the same email address you used in the "Send an email" action) for the final "Meeting Minutes and Gift Draft" email.
    *   Verify that the final email contains well-formatted meeting minutes in HTML and creative, contextually-relevant gift suggestions for action items.

3.  **Sample Meeting Transcript for Testing:**

    <details><summary>Click to expand Sample Meeting Transcript</summary>

    ```text
    Meeting: Project "Phoenix" - Sprint Planning - Deep Dive Edition!

    Attendees:  Maria (Project Manager),  David (Lead Developer),  Sophia (UX Designer),  Ethan (QA Tester)

    [Extended Watercooler Conversation - Start - Get Ready for Details!]

    Maria:  Good morning, team Phoenix!  Hope everyone had a fantastic weekend and is feeling energized for our sprint planning.  Let's kick things off with a little weekend recap – anyone do anything interesting? David, you’re up first!

    David:  Morning Maria, and team!  Interesting weekend?  Understatement!  So, remember I mentioned hiking last time? This weekend, I tackled the "Devil's Tooth Trail" – it’s a beast!  Seriously steep incline, rocky terrain, the whole nine yards.  Started Saturday morning, packed a ridiculous amount of water and protein bars.  The views from the summit were absolutely breathtaking – panoramic vista of the whole valley, you could see for miles.  Took some amazing photos, might even use one as my desktop background.  But… and here’s the kicker… about halfway down, I completely twisted my ankle.  OUCH!  Had to hobble the rest of the way, took me hours.  Ended up icing it all of Sunday, couldn’t walk properly until this morning.  So, beautiful hike, stunning views, epic fail on the descent.  Learned my lesson: hiking boots with better ankle support are now priority number one on my shopping list!  How about you, Sophia?  Less… physically traumatic, I hope?

    Sophia:  (Laughs) Oh David, you’re a trooper!  Sounds intense!  My weekend was… decidedly less strenuous.  I had a glorious, artsy, indoor weekend.  You know I’ve been getting into Japanese woodblock printing lately?  Well, I found this amazing online workshop with a master printmaker from Kyoto!  It was a two-day intensive, all virtual.  Spent Saturday and Sunday completely immersed in carving cherry wood blocks, mixing traditional pigments, and learning the Ukiyo-e techniques.  It's SO meticulous, every line has to be perfect.  My hands are a little sore from carving, but I created two prints that I’m actually really proud of – one of Mount Fuji at sunset, and another of stylized koi fish.  Might frame them for my apartment.  Completely different world from UX design, so creatively fulfilling.  Totally recharged my batteries.  Ethan, did you conquer any digital worlds this weekend?

    Ethan:  Sophia, woodblock printing sounds incredibly cool and…patient!  My weekend was pure digital mayhem, as predicted.  "Galactic Empires Online: Voidbringer Expansion" dropped Friday night.  And… let’s just say sleep was optional.  I joined a new guild – "The Quantum Crusaders" – they are hardcore.  We spent basically the entire weekend coordinating raids, strategizing fleet deployments, mining asteroids, and battling rival guilds for control of the Andromeda Galaxy (virtually, of course!).  Pulled two all-nighters, fueled by energy drinks and sheer willpower.  My apartment looks like a disaster zone of empty cans and snack wrappers, and I think my eyes are permanently square now, but… we conquered a whole new sector of space!  Top of the leaderboard, baby!  So, yeah, productive weekend in its own… unique way.  Maria, after all that adventure and digital domination, what did project management extraordinaire get up to?

    Maria:  (Chuckles)  Ethan, “digital mayhem” – I love it!  My weekend was… a bit more grounded in reality.  Remember I mentioned flatpack furniture last week?  Well, the saga continues.  This time, it was a bookshelf.  Seemed simple enough, right?  WRONG.  Instructions were cryptic hieroglyphics, Allen key stripped halfway through, and I’m pretty sure I installed one of the side panels upside down.  Spent hours wrestling with particleboard and tiny screws.  At one point, I considered just setting the whole thing on fire and ordering pre-assembled furniture online.  But… stubbornness prevailed.  After much cursing, sweat, and a near-existential crisis involving cam locks, I actually… assembled it!  It’s standing upright, miraculously.  A little wobbly, maybe, and slightly… asymmetrical, but it’s a bookshelf!  So, weekend achievement unlocked:  Barely Functional Bookshelf Construction.  Seriously considering hiring a professional furniture assembler for anything else that comes in a flatpack box in the future.  Okay team, enough about our weekends of hiking mishaps, artistic endeavors, digital conquests, and furniture failures!  Let’s actually get to the *real* project – Project "Phoenix" Sprint Planning.

    [Extended Watercooler Conversation - End / Sprint Planning - Start - Back to Business!]

    Maria:  Right, so, for Project "Phoenix," our sprint goal for this week remains focused on completing the user authentication module and finalizing the user profile setup.  David, given your… eventful hiking trip, are you still on track with the authentication module development update?  Need any… ankle-related accommodations? (winks)

    David:  (Chuckles) Ankle is… mostly functional for coding purposes, Maria.  Yes, authentication module is still progressing.  Error handling and security checks are underway.  Unit tests are next on the list.  Still aiming for QA readiness by Wednesday, even with the slightly hobbled developer.

    Sophia:  Excellent!  UX side is ready to support.  User profile designs and the style guide are finalized and polished.  I can share the style guide document with the development team first thing this morning to ensure everyone is aligned on the visual aspects.

    Ethan:  QA is gearing up as well. Test cases for user authentication and profile setup are nearing completion.  We’ll be ready to hit the ground running with testing as soon as David and Sophia give us the green light.  Will prioritize security and those pesky edge cases, as always.

    Maria:  Fantastic. Decisions: Sprint goal confirmed: User Authentication and User Profile Module.  Target QA readiness: Wednesday.

    Action Items:
    1. David: Finish error handling, security checks, and comprehensive unit tests for the Authentication Module. (Due: Wednesday)
    2. Sophia: Distribute the finalized User Profile Design Style Guide document to David and the development team. (Due: Today - Immediately after this meeting)
    3. Ethan: Complete, finalize, and share the detailed QA Test Cases document for User Authentication and User Profile Modules with the team. (Due: Tuesday Morning)
    4. Maria: Schedule a brief daily stand-up meeting for the rest of the week (starting tomorrow) to monitor sprint progress, identify and resolve any roadblocks promptly. (Due: Today - Calendar invites to be sent out by end of day)

    Maria:  Great plan, team.  Let's stay in close communication throughout the week.  Please update progress in our project channel daily.  Let’s collaborate effectively, support each other, and make this sprint another success for Project Phoenix!  Any final thoughts or questions before we adjourn?

    David:  Just need copious amounts of coffee and maybe a better chair for my ankle.  But code-wise, we’re good.

    Sophia:  Looking forward to seeing the authentication and profile modules come to life!

    Ethan:  Bring on the bugs!  QA team is ready to squash them all!

    Maria:  (Smiling)  That’s the spirit!  Alright team, meeting adjourned.  Go forth and conquer this sprint!

    Meeting Adjourned.
    ```
    </details>

4.  **AI Prompt:**
    *   You can find and review the AI Builder Text Generation Prompt "MeetingMinutesAndGiftGenerator" within the imported solution under "AI Prompts".

## Category Justification:

This project is submitted for consideration in the following categories:

*   **Best in Automation:** The core value proposition is automating the time-consuming task of creating meeting minutes and action items, streamlining meeting follow-up and improving team efficiency.
*   **Best in AI:**  The project leverages AI Builder's Text Generation in a novel and creative way to not only summarize information but also to generate empathetic and human-centric outputs (gift suggestions) based on nuanced conversational context.
*   **Best in Applications:**  The solution delivers a functional, end-to-end application for generating meeting minutes and gift suggestions, addressing a real-world business need through a user-friendly, seamless email-based delivery.
*   **Best in Power (Optional):** The solution effectively integrates multiple components of the Power Platform – Power Automate and AI Builder – to create a cohesive and valuable business solution.

## Team Members:
@CarlKho-Minerva

## Known Issues/Limitations:

*   HTML formatting in emails may vary slightly depending on the recipient's email client.  Basic HTML tags are used for formatting, but full CSS or complex HTML rendering is not guaranteed across all email clients.
*   Action item parsing relies on simple text-based identification and may not capture all action items in complex or unstructured transcripts perfectly.
*   Gift suggestions are generated based on AI interpretation of the transcript and may sometimes be less relevant or creative than desired. Further prompt refinement and training data could improve gift suggestion quality.
*   The current version is triggered manually.  Future enhancements could include automated triggering from meeting platforms (e.g., Teams) for a fully seamless experience.

## Future Enhancements:

*   **Enhanced HTML Email Formatting:** Explore more robust HTML email templates or libraries to improve visual presentation and cross-client compatibility.
*   **Automated Triggering:** Implement automated flow triggering from Teams meeting recordings or calendar events for a fully seamless, hands-free experience.
*   **Dataverse Integration:**  Utilize Dataverse to store meeting minutes, transcripts, user preferences, and track gift suggestions for better data management and reporting.
*   **Improved Gift Suggestion Logic:** Further refine the AI prompt and potentially explore fine-tuning AI models with more data to generate even more creative, personalized, and contextually relevant gift suggestions.
*   **User Interface in Power Apps:** Develop a user-friendly Canvas App interface to allow users to input meeting transcripts, review generated minutes and gift suggestions, and customize output options.
*   **Integration with Gift Vendor APIs:** Explore integration with APIs of online gift vendors to enable automated gift ordering and delivery based on AI suggestions (for a more advanced, e-commerce focused application).
