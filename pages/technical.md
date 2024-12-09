--- 
title: Technical Information
layout: about
permalink: /technical.html
---

# Content, Context, and Users (DEMO)

This digital collection consists of six oral history interviews (audio recordings), their corresponding transcripts, 1-5 objects that accompany each interview. These mixtures of interviews, transcripts, and object files are the content of the digital collection. Some of the interviewees are faculty at Indiana University, some farmers, some community members with trees on their property, and some are professionals who work with these fruits as part of their foodways-focused careers.

This collection was designed by Madison Cissell, a student of folklore and library science who has research interests in pawpaws and persimmons, specifically their communities of cultivation and use. The collection was designed for those who are interested in learning about the different ways pawpaws and persimmons are used in material culture. This digital space was also envisioned to be a place where farmers can listen to stories about the growing, grafting, and cultivation processes that their peers utilize in their own efforts of cultivation. 

Some interviews will also touch on folkways related to pawpaws and persimmons, and these recordings could be of interest to those interested in foodways folklore. With further development, this collection could be built into a learning commons about native foodways. The oral histories highlight multiple perspectives and relationships to the fruits, making it a landing site for an audience with a plethora of interests and specialties as they relate to pawpaws and persimmons. 

Although pawpaws and persimmons are known colloquially throughout southern Indiana and neighboring Kentucky and Ohio, these fruits are widely unknown on a national and international level (except for those familiar with the Asian persimmon). Even folks who reside in the Ohio Valley may have a basic understanding of the fruits and their flavor, not many are privvy to the folklore and lifeways of those who interact with the fruits. 

I was first introduced to pawpaws by my grandfather, who grows them in a grove in Louisville, Kentucky. He has had success with his fruits, and their uniqueness and invisibility in American/Midwestern-Southern culture, despite their indigeneity to this very region, has driven me to create this commons for all things pawpaws and persimmons.

# Visualization Made in Flourish  

{% include feature/image.html objectid="<div class="flourish-embed flourish-word-cloud" data-src="visualisation/20008789"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/20008789/thumbnail" width="100%" alt="word-cloud visualization" /></noscript></div>" %}

You can few this visualization in Flourish by following **[this link](https://public.flourish.studio/visualisation/20008789/)**. 

I chose to create a word cloud from my current dataset for a few reasons. First, I think the technical issues I have been running into with Flourish’s data visualization tools is due to most of my data being descriptive and qualitative, not numerical. Originally, I wanted to create visualizations that would compare the number of photographs that featured a subject that either had an obstructed or non-obstructed face. The largest ethical concern the digitization of this archive presents is centered around the reproduction of these images, and scanning and uploading reproductions of these photos could prove to only enhance the harm already done to them. Additionally, the women depicted in the archive have already been “invisiblized”, ghostly images of erased women. Their identities (pregnant, woman, non-white), too, already vulnerable and now additionally erased by the obstruction of their face, their key identifying feature. The frequency of the subject’s facial identity being obstructed could contribute to the conversations already taking place in this archival process. However, because my metadata only describes “facial obstruction” as either “yes” or “no”, I would need to re-configure my dataset to meet the requirements for visualization (I think). But I think it would be illuminating to see how often subjects’ faces are obstructed. At first, I thought this was a rare occurrence, but in the first batch of data entry, I found it to be more common than I initially realized.  

Similarly, I wanted to visualize the frequency of a race descriptor being employed by the seller of the photographs. This, too would require me to re-configure, as of right now the column “seller race description” only features “None” or “Black” for each data entry, and does not utilize numerical values. However, I do think it is important to illuminate the frequency of these descriptions, and I want to somehow point out that the sellers never label seemingly White or White-coded as “White”, but they always label Black or Black-coded women as “Black”.  

I settled on a word cloud visualization because I trusted that I would be able to successfully produce a visualization, given that my data is mainly descriptive and text-based. I like making word clouds because they easily visualize the textual impact certain words have on the larger body of work one consumes. World clouds help me make sense of texts that leave me wanting to dive even deeper into the content and the author. I chose to include the columns describing “creator”, “context”, and “pose description”. The context, authored by me, describes everything happening in the image outside of the central subject(s), which are always the pregnant person/mother and/or the baby. “Context” describes additional individuals in the photo, the background, and the setting. “Pose description”, also authored by myself, describes the pose of the central subject(s). I chose to include “creator” in my visualization to send the message that although I have created descriptions for these photos, the person who took the photograph and the subjects within are unknown, for all the objects. Because word clouds specialize in frequency of words, this will always be the largest word in the visualization, serving as a constant reminder that assumptions should be critiqued, as I am describing something that is unknown to me.  

My current dataset is not organized in a way where I can produce categorized text colors for the words within the cloud, but this is something that I could tweak in the future to distinguish which words are coming from context vs. pose description. I like that the words look jumbled, and that my mind automatically tries to create sentences from the words that populate the cloud. This highlights the confusion, piecemeal, and guesswork I am experiencing as I organize the data. I hope that my visualization shows the audience some key subject terms in the archive, it is interesting to me that the frequency of words like “belly” and “baby” mirror the search terms that Emily employed when she found these photos. Additionally, the world cloud, to me, automatically points out the presence of the hospital and medical staff and equipment as it relates to the archive. This dataset is not complete, but the initial entries contain several photos depicting active labor and its immediate aftermath, and so far, all depictions of labor in the dataset have taken place in a hospital, and the “home” descriptor has only been employed pre- or postnatal. Emily and I are interested in the representation of home vs. hospital births in the archive.  

My only other experience with word clouds has been via Voyant’s textual analysis visualizations. I recently used it to analyze some personal correspondence I received in the mail- it was fun! The only initial “limitation” I saw was that, out of habit, I went to click on the word cloud to see how it would rearrange the words, and I immediately realized that this was a specific feature to Voyant. I appreciated that even though my uploaded data is not structured in accordance to Flourish’s template, I could still use the tool by just copying and pasting my corpus into Flourish. I want to try the color-coded visualization out once things are in order, as I think this is an advantage over Voyant, since as far as I am aware, the colors assigned to words in their visualizations are arbitrary.


# Documentation of elements
## Required CollectionBuilder elements

**Objectid**
- **Cardinality:** 1 entry per record 
- **Obligation:** Mandatory 
- **Content guidelines:** Entry should start with the project code, tpi (the pregnant image), followed by its assigned order in the collection.
- **Applicable controlled vocabularies:** N/A 
- **Mapping to Dublin Core:** “Identifier” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/identifier/"> Dublin Core Standards for "Identifier" </a>
**Example:** The archive is organized by the envelopes that were mailed to Emily. The 10th item in the collection is a photograph. This photograph is the 8th photograph found in Envelope 1. This object's **id** would be **tpi010** since it is the 10th item in the collection.

**Filename** 
- **Cardinality:** 1 entry per record
- **Obligation:** Mandatory 
- **Content guidelines:** Entry should start with the project code, tpo (the pregnant object), followed by its assigned order in the collection.The value must exactly match the actual filename of the file in the “objects” directory with the appropriate file extension given the format of the file.
- **Applicable controlled vocabularies:** N/A 
- **Mapping to Dublin Core:** “Identifier” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/identifier/"> Dublin Core Standards for "Identifier" </a>
**Example:** The archive is organized by the envelopes that were mailed to Emily. The 10th item in the collection is a photograph. This photograph is the 8th photograph found in Envelope 1. This object's **filename** would be **tpo010.jpg** since it is the 10th item in the collection.


**Title**
- **Cardinality:** 1 entry per record
- **Obligation:** Mandatory 
- **Content guidelines:** Entry should be the name of the object as it appears in the envelope. All items are titled as either an Envelope, Description, or Photo.  
- **Applicable controlled vocabularies:** N/A 
- **Mapping to Dublin Core:** “Title” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/title/"> Dublin Core Standards for "Title" </a> 
- **Example:** The archive is organized by the envelopes that were mailed to Emily. The 10th item in the collection is a photograph. This photograph is the 8th photograph found in Envelope 1. This object's **title** would be **Photo 08** since it is the 8th photo in the collection.

**Format** 
- **Cardinality:** 1 entry per record
- **Obligation:** Mandatory
- **Content guidelines:** This field indicates the item’s media type, which will vary depending on if it is a compound object or an image. Format will follow a controlled vocabulary, which will utilize a list of Internet Media Types provided by Dublin Core and the vocabulary for compound objects.
- **Applicable controlled vocabularies:** Internet Media Types (MIME). Common values for this collection will be: audio/mp3; image/jpg, or application/pdf. All **images** in the collection will utilize **image/jpeg** as their format. All **compound objects** will utilize **compound_object** as their format. 
- **Mapping to Dublin Core:** “Format” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/elements11/format/"> Dublin Core Standards for "Format" </a>
- **Example:** audio/mp3

## CollectionBuilder visualization elements

**Subjects (subject)**
- **Cardinality:** Up to 10 entries per record.
- **Obligation:** Mandatory
- **Content guidelines:** These entries will be topics related to the item. This field allows for multiple subjects (up to 10), each should be separated by a semicolon (;). Subject entries should be selected using the Library of Congress subject headings, which is a controlled vocabulary.
- **Applicable controlled vocabularies:** Library of Congress subject headings
- **Mapping to Dublin Core:** “Subject” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/elements11/subject/"> Dublin Core Standards for "Subject" </a>
- **Example:** portrait; color;. 

**Location**
- **Cardinality:** 1 entry per record
- **Obligation:** Mandatory
- **Content guidelines:** The name of the city or town listed in the return mailing address employed by the seller, followed by the federally recognized two-letter state and territory abbreviation.
- **Applicable controlled vocabularies:** N/A
- **Mapping to Dublin Core:** “Location, Period, or Jurisdiction” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/"> Dublin Core Standards for “Location, Period, or Jurisdiction” </a> 
- **Example:** Lakewood, CA 

**Map (latitude)**
- **Cardinality:** 1 entry per record
- **Obligation:** Mandatory 
- **Content guidelines:** A geographic coordinate of the return mailing address employed by the seller.
- **Applicable controlled vocabularies:** N/A	
- **Mapping to Dublin Core:** “Location, Period, or Jurisdiction” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/"> Dublin Core Standards for “Location, Period, or Jurisdiction” </a> 
- **Example:** 33.8536 


**Map (longitude)**
- **Cardinality:** 1 entry per record 
- **Obligation:** Mandatory
- **Content guidelines:** A geographic coordinate of the return mailing address employed by the seller specified by the east-west position of the interview site.
- **Applicable controlled vocabularies:** N/A 
- **Mapping to Dublin Core:** “Location, Period, or Jurisdiction” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/"> Dublin Core Standards for “Location, Period, or Jurisdiction” </a> 
- Example: -118.134 

## Optional CollectionBuilder elements (DEMO)

**Description (Synopsis)**
- **Cardinality:** 1 entry per record
- **Obligation:** Optional
- **Content guidelines:** This field should be a brief summary/synopsis of the interview in 3-5 sentences. It should cover major points of the interview. If being used for an object, it should briefly describe the object and its significance.
- **Applicable controlled vocabularies:** N/A 
- **Mapping to Dublin Core:** “Description” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/description/"> Dublin Core Standards for "Description" </a>
- **Example:** Darren Bender-Beauregard provides a background on growing up Mennonite on the East Coast before attending Goshen College. He now resides in Paoli, Indiana on Brambleberry Farm, where is family has a homestead and sells pawpaw and persimmon seedlings. Darren describes his knowledge of pawpaws and persimmons, the grafting process, and his agricultural network. 

**Interviewee** 
- **Cardinality:** 1 entry per record 
- **Obligation:** Optional, but should be used for interview and transcript records. 
- **Content guidelines:** This should be the interviewee’s full or preferred name. 
- **Applicable controlled vocabularies:** N/A 
- **Mapping to Dublin Core:** “Contributor” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/contributor/"> Dublin Core Standards for "Contributor" </a>  
- **Example:** Darren Bender-Beauregard 

**Interviewer**
- **Cardinality:** 1 entry per record 
- **Obligation:** Optional, but should be used for interview and transcript records. 
- **Content guidelines:** This should be the interviewer’s full or preferred name. 
- **Applicable controlled vocabularies:** N/A  
- **Mapping to Dublin Core:** “Creator” <a href="https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/creator/"> Dublin Core Standards for "Creator" </a> 
- **Example:** Madison Cissell 