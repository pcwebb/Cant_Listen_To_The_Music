#########################
Can't Listen To The Music
#########################

********
Personas
********

Byron is a 63 year old music enthusiast. He has a full time job, which
consumes much of his time but his primary passion is collecting music.
He loves and collects all types of music from country to jazz. His tastes
are eclectic. Byron has amassed thousands of albums in his collection and
would like to spend less time working on his hobby and more time enjoying it.


*****************
Problem Scenarios
*****************

Byron would like to reduce the time spent to cataloging his collection
in order to spend more time listening and enjoying his music.


Current Alternatives
====================

When Byron is able to carve out some time to listen to his collection,
he is not always able to find the exact song or band he would like to
listen to. He selects is the first song he encounters that closely matches
the genre he wants. For example, if he could not find Bettye LaVette he
would substitute with Billie Holiday as a quick selection although Billie
Holiday was not his first choice.


Value Proposition
==================

Creating a digitized index, cataloging the location, album, song and artist,
Byron could better locate and enjoy a specific music selection making
better use of his limited timeframes. 


************
User Stories
************

As Byron the music collector, I want to easily catalog and access my vast
amount of recorded music, so that I can select specific music quickly and
increase my enjoyment of my hobby.


Acceptance Story
================

| **Scenario 1:** Inputting the albums
| **Given** that I have an new album
| **And** I would like to catalog it into a program
| **When** I click the  *New* button
| **Then** I will be taken to a form screen to input my album information by
 filling in an *Album*, *Song*, *Artist*, *Location*, and *Genre*
| **And** the *Date Cataloged* will auto-fill.

| Scenario 2: Selecting and deleting a song
| **Given that I would like to play a song from my collection
| **And I would like to use specific parameters
| **When I click the *Select* button
| **Then I will be taken to a form to input my parameters (*Album*, *Song*,
 *Artist*, *Location*, and/or *Genre*)
| **And a list with *Album*, *Song*, *Artist*, *Location*, and or *Genre*
 will generate based on those selected parameters
| **And a *Delete* button will appear beside each song which will delete entry
 when selected
| **And an *Accessed * button will appear beside each song which will auto-fill
 when selected

| **Scenario 3:** Songs recently accessed
| **Given** that I have digitally accessed songs from my collection
| **When** I click the *Recently Accessed* button
| **Then** I will be taken to a list indicated my most recent selection for the
 past 3 months
| **And** this list will include *Album*, *Song*, *Artist*, *Location*, *Genre* 
| **And** the *Accessed* button will appear which will auto-fill if selected


