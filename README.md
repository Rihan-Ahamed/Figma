# Ex09 Event Registration Web Application
## Date: 17/05/2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
~~~
Frame 1:
HMTL:
<div style="width: 412px; height: 917px; position: relative; background: #8EEFEA; overflow: hidden">
  <img style="width: 473px; height: 473px; left: -29px; top: 459px; position: absolute" src="https://placehold.co/473x473" />
  <div style="width: 441px; height: 68px; left: -14px; top: 108px; position: absolute; text-align: center; color: #042044; font-size: 32px; font-family: REM; font-weight: 700; word-wrap: break-word">🤖 Chatbot Sprint: Build Your Bot in 60 Minutes!<br/></div>
  <div style="width: 385px; height: 80px; left: 10px; top: 218px; position: absolute; text-align: center; color: black; font-size: 26px; font-family: Signika Negative SC; font-weight: 400; word-wrap: break-word">🚀 Turn your imagination into a working chatbot — no coding required! </div>
</div>

CSS:
import React from "react";
import styled from "styled-components";

const StyledChatbotconceptillustration1 = styled.div`
  width: 473px;
  height: 473px;
  left: -29px;
  top: 459px;
  position: absolute;
`;

const StyledChatbotsprintbuildyourbotin60minutesspan = styled.span`
  color: #042044;
  font-size: 32px;
  font-family: REM;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledTurnyourimaginationintoaworkingchatbotnocodingrequiredspan = styled.span`
  color: black;
  font-size: 26px;
  font-family: Signika Negative SC;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledAndroidCompact1 = styled.div`
  width: 412px;
  height: 917px;
  position: relative;
  background: #8EEFEA;
  overflow: hidden;
`;

export const AndroidCompact1 = () => {
  return (
    <StyledAndroidCompact1>
      <StyledChatbotconceptillustration1  src="https://placehold.co/473x473"/>
      <StyledChatbotSprintBuildYourBotin60Minutes>🤖 Chatbot Sprint: Build Your Bot in 60 Minutes!<br/></StyledChatbotSprintBuildYourBotin60Minutes>
      <StyledTurnyourimaginationintoaworkingchatbotnocodingrequired>🚀 Turn your imagination into a working chatbot — no coding required! </StyledTurnyourimaginationintoaworkingchatbotnocodingrequired>
    </StyledAndroidCompact1>
  );
};


Frame 2:
HTML:
<div style="width: 412px; height: 917px; position: relative; background: #8EEFEA; overflow: hidden; outline: 1px black solid; outline-offset: -1px">
  <img style="width: 402px; height: 60px; left: 10px; top: 26px; position: absolute" src="https://placehold.co/402x60" />
  <div style="width: 355px; height: 333px; left: 29px; top: 155px; position: absolute"><span style="color: black; font-size: 26px; font-family: Signika Negative SC; font-weight: 400; word-wrap: break-word">📍 </span><span style="color: black; font-size: 24px; font-family: Signika Negative SC; font-weight: 400; word-wrap: break-word">Venue: Saveetha Engineering College, Seminar Hall – Block A    🕗 Time: 8:00 AM to 10:00 AM    📅 Date: [Add your event date here]    🎟️ Open to: All college students (Limited seats – first come, first served!)</span></div>
  <img style="width: 271px; height: 271px; left: 10px; top: 607px; position: absolute" src="https://placehold.co/271x271" />
</div>

CSS:
import React from "react";
import styled from "styled-components";

const StyledRectangle = styled.div`
  width: 402px;
  height: 60px;
  left: 10px;
  top: 26px;
  position: absolute;
`;

const StyledVenuesaveethaengineeringcollegeseminarhallblockatime800amto1000amdateaddyoureventdatehereopentoallcollegestudentslimitedseatsfirstcomefirstservedspan01 = styled.span`
  color: black;
  font-size: 26px;
  font-family: Signika Negative SC;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledVenuesaveethaengineeringcollegeseminarhallblockatime800amto1000amdateaddyoureventdatehereopentoallcollegestudentslimitedseatsfirstcomefirstservedspan02 = styled.span`
  color: black;
  font-size: 24px;
  font-family: Signika Negative SC;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledChatbot97332021 = styled.div`
  width: 271px;
  height: 271px;
  left: 10px;
  top: 607px;
  position: absolute;
`;

const StyledAndroidCompact2 = styled.div`
  width: 412px;
  height: 917px;
  position: relative;
  background: #8EEFEA;
  overflow: hidden;
  outline: 1px black solid;
  outline-offset: -1px;
`;

export const AndroidCompact2 = () => {
  return (
    <StyledAndroidCompact2>
      <StyledRectangle  src="https://placehold.co/402x60"/>
      <StyledVenueSaveethaEngineeringCollegeSeminarHallBlockATime800AMto1000AMDateAddyoureventdatehereOpentoAllcollegestudentsLimitedseatsfirstcomefirstserved><StyledVenuesaveethaengineeringcollegeseminarhallblockatime800amto1000amdateaddyoureventdatehereopentoallcollegestudentslimitedseatsfirstcomefirstservedspan01>📍 </StyledVenuesaveethaengineeringcollegeseminarhallblockatime800amto1000amdateaddyoureventdatehereopentoallcollegestudentslimitedseatsfirstcomefirstservedspan01><StyledVenuesaveethaengineeringcollegeseminarhallblockatime800amto1000amdateaddyoureventdatehereopentoallcollegestudentslimitedseatsfirstcomefirstservedspan02>Venue: Saveetha Engineering College, Seminar Hall – Block A        🕗 Time: 8:00 AM to 10:00 AM        📅 Date: [Add your event date here]        🎟️ Open to: All college students (Limited seats – first come, first served!)</StyledVenuesaveethaengineeringcollegeseminarhallblockatime800amto1000amdateaddyoureventdatehereopentoallcollegestudentslimitedseatsfirstcomefirstservedspan02></StyledVenueSaveethaEngineeringCollegeSeminarHallBlockATime800AMto1000AMDateAddyoureventdatehereOpentoAllcollegestudentsLimitedseatsfirstcomefirstserved>
      <StyledChatbot97332021  src="https://placehold.co/271x271"/>
    </StyledAndroidCompact2>
  );
};


Frame 3:
HTML:

<div style="width: 412px; height: 917px; position: relative; background: #8EEFEA; overflow: hidden">
  <img style="width: 402px; height: 60px; left: 10px; top: 24px; position: absolute" src="https://placehold.co/402x60" />
  <img style="width: 231px; height: 231px; left: 95px; top: 686px; position: absolute" src="https://placehold.co/231x231" />
  <div style="width: 352px; height: 425px; left: 35px; top: 131px; position: absolute"><span style="color: black; font-size: 26px; font-family: Signika Negative SC; font-weight: 400; word-wrap: break-word">🛠️ What You'll Learn & Do:<br/></span><span style="color: black; font-size: 26px; font-family: Signika Negative SC; font-weight: 400; word-wrap: break-word">✨ Quick Crash Course – Understand chatbot building blocks & flow logic<br/>👨‍🏫 Hands-on Session – Build your bot step-by-step with live guidance<br/>🤖 AI Basics – Learn how bots understand and reply using NLP<br/>🎁 Build & Take Away – Your own working chatbot + Certificate</span></div>
</div>

CSS:

import React from "react";
import styled from "styled-components";

const StyledSaveethalogo = styled.div`
  width: 402px;
  height: 60px;
  left: 10px;
  top: 24px;
  position: absolute;
`;

const StyledChatbot91952561 = styled.div`
  width: 231px;
  height: 231px;
  left: 95px;
  top: 686px;
  position: absolute;
`;

const StyledWhatyoulllearndoquickcrashcourseunderstandchatbotbuildingblocksflowlogichandsonsessionbuildyourbotstepbystepwithliveguidanceaibasicslearnhowbotsunderstandandreplyusingnlpbuildtakeawayyourownworkingchatbotcertificatespan01 = styled.span`
  color: black;
  font-size: 26px;
  font-family: Signika Negative SC;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledWhatyoulllearndoquickcrashcourseunderstandchatbotbuildingblocksflowlogichandsonsessionbuildyourbotstepbystepwithliveguidanceaibasicslearnhowbotsunderstandandreplyusingnlpbuildtakeawayyourownworkingchatbotcertificatespan02 = styled.span`
  color: black;
  font-size: 26px;
  font-family: Signika Negative SC;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledAndroidCompact3 = styled.div`
  width: 412px;
  height: 917px;
  position: relative;
  background: #8EEFEA;
  overflow: hidden;
`;

export const AndroidCompact3 = () => {
  return (
    <StyledAndroidCompact3>
      <StyledSaveethalogo  src="https://placehold.co/402x60"/>
      <StyledChatbot91952561  src="https://placehold.co/231x231"/>
      <StyledWhatYoullLearnDoQuickCrashCourseUnderstandchatbotbuildingblocksflowlogicHandsonSessionBuildyourbotstepbystepwithliveguidanceAIBasicsLearnhowbotsunderstandandreplyusingNLPBuildTakeAwayYourownworkingchatbotCertificate><StyledWhatyoulllearndoquickcrashcourseunderstandchatbotbuildingblocksflowlogichandsonsessionbuildyourbotstepbystepwithliveguidanceaibasicslearnhowbotsunderstandandreplyusingnlpbuildtakeawayyourownworkingchatbotcertificatespan01>🛠️ What You'll Learn & Do:<br/></StyledWhatyoulllearndoquickcrashcourseunderstandchatbotbuildingblocksflowlogichandsonsessionbuildyourbotstepbystepwithliveguidanceaibasicslearnhowbotsunderstandandreplyusingnlpbuildtakeawayyourownworkingchatbotcertificatespan01><StyledWhatyoulllearndoquickcrashcourseunderstandchatbotbuildingblocksflowlogichandsonsessionbuildyourbotstepbystepwithliveguidanceaibasicslearnhowbotsunderstandandreplyusingnlpbuildtakeawayyourownworkingchatbotcertificatespan02>✨ Quick Crash Course – Understand chatbot building blocks & flow logic<br/>👨‍🏫 Hands-on Session – Build your bot step-by-step with live guidance<br/>🤖 AI Basics – Learn how bots understand and reply using NLP<br/>🎁 Build & Take Away – Your own working chatbot + Certificate</StyledWhatyoulllearndoquickcrashcourseunderstandchatbotbuildingblocksflowlogichandsonsessionbuildyourbotstepbystepwithliveguidanceaibasicslearnhowbotsunderstandandreplyusingnlpbuildtakeawayyourownworkingchatbotcertificatespan02></StyledWhatYoullLearnDoQuickCrashCourseUnderstandchatbotbuildingblocksflowlogicHandsonSessionBuildyourbotstepbystepwithliveguidanceAIBasicsLearnhowbotsunderstandandreplyusingNLPBuildTakeAwayYourownworkingchatbotCertificate>
    </StyledAndroidCompact3>
  );
};

Frame 4:

HTML:
<div style="width: 412px; height: 917px; position: relative; background: #8EEFEA; overflow: hidden">
  <img style="width: 402px; height: 60px; left: 10px; top: 32px; position: absolute" src="https://placehold.co/402x60" />
  <img style="width: 235px; height: 235px; left: 47px; top: 605px; position: absolute" src="https://placehold.co/235x235" />
  <div style="width: 412px; height: 421px; left: 0px; top: 121px; position: absolute"><span style="color: black; font-size: 26px; font-family: Signika Negative SC; font-weight: 400; word-wrap: break-word">🎉 Perks:    ✅ No experience needed    ✅ Free participation    ✅ Certificate & resource kit    ✅ Live mentoring & Q&A<br/><br/><br/>Spots are filling fast!    📲 Register Now: </span><span style="color: #3167EE; font-size: 26px; font-family: Signika Negative SC; font-weight: 400; word-wrap: break-word">evvents.saveetha.ac.in</span><span style="color: black; font-size: 26px; font-family: Signika Negative SC; font-weight: 400; word-wrap: break-word">    📧 Contact: eventsaveetha@gmail.con</span></div>
</div>


CSS:

import React from "react";
import styled from "styled-components";

const StyledSaveethalogo = styled.div`
  width: 402px;
  height: 60px;
  left: 10px;
  top: 32px;
  position: absolute;
`;

const StyledChatbot41963031 = styled.div`
  width: 235px;
  height: 235px;
  left: 47px;
  top: 605px;
  position: absolute;
`;

const StyledPerksnoexperienceneededfreeparticipationcertificateresourcekitlivementoringqaspotsarefillingfastregisternowevventssaveethaacincontacteventsaveethagmailconspan01 = styled.span`
  color: black;
  font-size: 26px;
  font-family: Signika Negative SC;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledPerksnoexperienceneededfreeparticipationcertificateresourcekitlivementoringqaspotsarefillingfastregisternowevventssaveethaacincontacteventsaveethagmailconspan02 = styled.span`
  color: #3167EE;
  font-size: 26px;
  font-family: Signika Negative SC;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledPerksnoexperienceneededfreeparticipationcertificateresourcekitlivementoringqaspotsarefillingfastregisternowevventssaveethaacincontacteventsaveethagmailconspan03 = styled.span`
  color: black;
  font-size: 26px;
  font-family: Signika Negative SC;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledAndroidCompact4 = styled.div`
  width: 412px;
  height: 917px;
  position: relative;
  background: #8EEFEA;
  overflow: hidden;
`;

export const AndroidCompact4 = () => {
  return (
    <StyledAndroidCompact4>
      <StyledSaveethalogo  src="https://placehold.co/402x60"/>
      <StyledChatbot41963031  src="https://placehold.co/235x235"/>
      <StyledPerksNoexperienceneededFreeparticipationCertificateresourcekitLivementoringQASpotsarefillingfastRegisterNowevventssaveethaacinContacteventsaveethagmailcon><StyledPerksnoexperienceneededfreeparticipationcertificateresourcekitlivementoringqaspotsarefillingfastregisternowevventssaveethaacincontacteventsaveethagmailconspan01>🎉 Perks:        ✅ No experience needed        ✅ Free participation        ✅ Certificate & resource kit        ✅ Live mentoring & Q&A<br/><br/><br/>Spots are filling fast!        📲 Register Now: </StyledPerksnoexperienceneededfreeparticipationcertificateresourcekitlivementoringqaspotsarefillingfastregisternowevventssaveethaacincontacteventsaveethagmailconspan01><StyledPerksnoexperienceneededfreeparticipationcertificateresourcekitlivementoringqaspotsarefillingfastregisternowevventssaveethaacincontacteventsaveethagmailconspan02>evvents.saveetha.ac.in</StyledPerksnoexperienceneededfreeparticipationcertificateresourcekitlivementoringqaspotsarefillingfastregisternowevventssaveethaacincontacteventsaveethagmailconspan02><StyledPerksnoexperienceneededfreeparticipationcertificateresourcekitlivementoringqaspotsarefillingfastregisternowevventssaveethaacincontacteventsaveethagmailconspan03>        📧 Contact: eventsaveetha@gmail.con</StyledPerksnoexperienceneededfreeparticipationcertificateresourcekitlivementoringqaspotsarefillingfastregisternowevventssaveethaacincontacteventsaveethagmailconspan03></StyledPerksNoexperienceneededFreeparticipationCertificateresourcekitLivementoringQASpotsarefillingfastRegisterNowevventssaveethaacinContacteventsaveethagmailcon>
    </StyledAndroidCompact4>
  );
};
~~~

## OUTPUT:
![alt text](<Screenshot 2025-05-18 183911.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
