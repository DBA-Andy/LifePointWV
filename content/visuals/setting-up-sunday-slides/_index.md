---
title: "Setting up Sunday Slides"
weight: 1
---

- Matthew will send his notes by Thursday morning, but there could be changes.  Final notes by noon on Saturday.
  - We work from his outline, not the notes in the e-mail.  Look for the highlighted items in his outline.  
    - If there are talking points between verses, that’s an indication the verses will be on separate slides.
- We download the worship slides from [Lifepoint's FTP server](https://gofile.me/6WE6j/VxLTcyStx)
  - We can either do this on our local machine and upload them to the mac mini (what I do) or we can download directly from the mac mini (benefit of only one transfer delay)
- We import the worship slides and add them to our new playlist
- We set up the sermon slides

## Creating the playlist
- Duplicate the list called "Duplicate this List!" by Right-Clicking on the list and selecting duplicate.

  ![Duplicate Playlist](./images/duplicate_playlist.png)
- Drag the Playlist to the desired Series folder, then right-click and rename it, based on the date of service.

  ![Rename Playlist](./images/rename_playlist.png)

## Downloading the worship slides
### As mentioned above, we can either download to our local machine and upload to the mac mini, or download directly to the mac mini
  - I've historically chosen to download to my machine then upload to the mac mini to minimize the number of places my google drive account is logged in.
  - Now that Lifepoint is putting everything on [Lifepoint's FTP server](https://gofile.me/6WE6j/VxLTcyStx), it might be just as fast to download there.
### Complete the download
  - Go to [Lifepoint's FTP server](https://gofile.me/6WE6j/VxLTcyStx).  There is no authentication that I'm aware of.
  - Double-click on "Series."
  - Double-click on the "Current Series."
  - Double-click on the "Date of Service" you need to download worship slides for.
  - Download the appropriate "PROPLAYLIST file"

  ![PROPLAYLIST download](./images/proplaylist_download.png)
### Upload to Mac Mini if you downloaded to your local machine (Optional)
  - While connected in teamviewer to the Mac Mini, click on "Files and Extras"

    ![File Transfer 1](./images/file_transfer1.png)
  - Click on "Open File Transfer"

    ![File Transfer 2](./images/file_transfer2.png)
  - Navigate to wherever you downloaded the file on your local machine, and the downloads folder on the mac mini (see screenshot above)
  - Select the file you wish to transfer and then click "Send"

    ![Send File](./images/send_file.png)
  - Once the transfer is complete, click "close."  
  ***NOTE*** You can continue to work on other things in the background while the transfer happens.

## Importing and setting up Worship Slides
  - Once you have gotten the worship slides file (PROPLAYLIST FILE) onto the Mac Mini, we're ready to import it into pro presenter, and add it to this week's playlist.
  - In ProPresenter, click on "File-> Import -> File"
    
    ![Import File](./images/file_importFile.png)
  - In the resulting dialogue box, navigate to the downloads folder and choose this week's PROPLAYLIST file.

    ![Select and Import File](./images/select_and_import_file.png)
  - Because of the way we name our playlists, vs the way LC names the PROPLAYLIST file, we see something like the below.  We name our playlist "MM-DD-YYYY" and they theirs "M.DD.YYYY AM" generally.
    
    ![Playlist Samples](./images/playlist_samples.png)
  - Select the LC Playlist we just imported so we can add the worship set to our playlist.
  - It's probably easiest to "add" everything and then remove what we don't want, so click on the first item, hold down the shift key, then click on the last item.

    ![Select all Items](./images/select_all_items.png)
  - Right-Click on the list of selected items, then click "Add to" then the Playlist we created for this week.

    ![Add to Playlist](./images/add_to_playlist.png)
  - We are now technically done with the "LC" playlist and could remove it from our view if we wanted by right-clicking and clicking "delete."
  - Left-Click on the playlist for the week we're setting up.
  - Compare the order in the playlist to the order in Planning Center online.
    - Planning Center

    ![Planning center order](./images/planning_center_order.png)
    - LC Playlist we downloaded from the FTP Site:
    
      ![LC Playlist](./images/LC_Playlist.png)
  - On rare occasions, we'll have a different worship set at Westerville than Lewis Center.  This week was one such week.  In comparing the screenshots above, you'll see we're doing "All for you", "The Lion And the Lamb", the "Pastoral Moment", then "Every Victory" for opening worship, and the closing song is "Son of Suffering."  See [Adding Songs from the Library](../adding-songs-from-the-library/_index.md) for more info.  Planning Center is King - What's in Planning Center is what we'll be doing on Sunday!
  - Once I have the worship songs in, I generally text Caleb and tell him what position in the playlist the worship songs are in.  MOST of the time, it's 4, 5, 6, and 11.  Note, in the screenshot, the headers for each portion of service also count as a position.
    
    ![count positions](./images/counting_positions.png)
  - Now, we have to make sure things are set up for "Westerville" instead of "Lewis Center."
    - For each song, we need to make sure the "Worship Look" Macro is properly selected.  For some, it is, for others it isn't.
      - Right-click on the background slide and look at "remove actions."  If it says "Worship Look" and doesn't have an ugly yellow yield sign with an !, it's good.
        - Good

        ![Good Macro Example](./images/good_macro_example.png)
        - Bad

        ![Bad Macro Example](./images/bad_macro_example.png)
    - ***NOTE*** It's ***most*** important to have the macro on the first song of the worship set and the closing song, but it's good practice to put them on all.  The macro changes from the countdown timer on the confidence monitor to lyrics on the confidence monitor.
    - For each song, we need to make sure we've applied the Westerville Theme.  The Macro is supposed to make sure the theme is good, but it doesn't always catch everything, so we err on the side of caution.
      - ***NOTE*** If you're doing this remotely on your computer, the "Open-Apple" command is the "Windows button."
      - Select the first slide (background) of the song, and hit "Open-Apple + A" to "select all."  You can also use use "Edit -> Select All" from the menu.
        - Once all the slides for that song are selected, Right-Click -> Themes -> WV Lyrics -> Theme Slide

          ![WV Lyrics](./images/wv_lyrics.png)
      - Repeat for each song in the worship set this week.

## Setting up Sermon Slides
  - As mentioned in the overview, Matthew will generally send his outline on Thursday, and send a final copy on Saturday.  The final copy should be compared against what you've already set up, if you set things up based on the Thursday copy, just to be safe.  Items highlighted yellow are what Matthew wants slides for.
  - Open Matthew's Outline
  - On the mac mini, unless it's a new series, I generally find it easier to just duplicate a previous week's sermon slides.
    - Open last week's playlist, right-click on the sermon slides, and click "Show in Library."
    - Right-Click on the slideshow and click "Duplicate."
    - Right-Click on the duplicate slideshow and click "Rename"
    - Change the date from last week to this week's date.
    - Right-Click on the new slideshow and "Add To" this week's playlist
  - Click back on this week's playlist
  - Now we remove all last week's slides from this week's slideshow.
    - We leave the slide for the series.  So I click on the slide ***after*** that, then scroll down to the bottom, hold down the shift key, and click on the slide before the title slide at the end of the presentation.
    - Right-Click and click "Delete."
  - Now we're ready to to add this week's "stuff."
    - The general flow tends to be POINT -> Versus to teach/support the point.  
    - Right-Click on the Series slide and click "Edit Slide" or click "Edit" in the Bar above the Libary

      ![edit sermon slides](./images/edit_sermon_slides.png)
    - From here, things get pretty repetitive:
      - Click the "Add Blank Slide" + symbol, then I usually use the "Labels Verse" theme, and either Point or Verse, depending on the context of the slide.

        ![Add blank slide](./images/add_blank_slide.png)
      - If it's a verse, and it won't all fit on 1 slide (usually more than about 6 lines), I count the number of lines and try to make the slides roughly even on number of lines.
        - We center the verse header, then left justify the actual verse.
        - I also generally center the text on the slide vertically.

          ![Verse Slide Layout](./images/verse_slide_layout.png)
        - To "Split a slide" there's a keyboard shortcut "Option + Enter."  If you're doing this remotely on a windows machine, it's "ALT+Enter."  I use this when it's a long verse that needs split to multiple slides.  Again, I count the number of lines, then try to split the lines evenly across some number of slides with 6 lines or less.
      - If it's a point slide, and the point is long, I'll usually try to split it onto two lines so it doesn't look "bad" on the projector.

        ![Point Slide Layout](./images/point_slide_layout.png)
    - Basically, you'll copy/paste from Matthew's outline to the slide -> format -> repeat.
