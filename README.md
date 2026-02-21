A Google-Translate version of this brilliant MyBB plugin.

# Family Control Panel
First off: this plugin was developed some time ago on behalf of and in collaboration with @berrie – she defined the detailed specifications, ideas, and functions, and has been using the plugin in her forums for years. <b>Thank you</b> for allowing me to publish the plugin. ♥

<hr />

This plugin extends your MyBB-RPG forum by allowing users to create their characters' families on a separate page and display them in their profile, divided by generations.

The new page can be accessed via yourforum.com/family.php 

<ul>
<li> Setting up a family account with general information
<li> Investment of individual family members, divided by generations
<li> Presentation of the family with all information in the character's profile.
<li> Automatic creation of a request thread for the family in the request subforum
<li> Filtering families based on information such as social class
<li> Filtering playable family members by age & gender
<li> Display of playable or unplayable members
<li> Existing family members can add themselves to the family with a single click.
<li> Family members can be reserved with one click.
<li> MyAlerts notification when a family member makes a reservation
<li> Display of existing family members with avatar & profile link
<li> If an individual request exists for a member, it can be linked.
<li> Family "owners" can release reservations again.
<li> Your own reservations will be displayed on the index.
<li> Specifying a default image for family members in the Admin CP
<li> Creator provides a picture for family members

</ul>

<h1>Requirements</h1>
Each player name may only be assigned <b>once</b>, as this is linked to the reservation system.

<h1>Make the plugin functional</h1>
<ul>
<li>Upload the plugin file to the specified folder <b>inc/plugins</b>.
<li>You upload the language files to the corresponding language folder.
<li>The plugin must now be installed and activated in the Admin CP under <b>Configuration - Plugins</b>.
<li>In the forum settings, you will now find – at the very bottom – settings for "Family Control Panel". Make your desired settings there.
</ul><br />

The plugin is now ready to use. If you've already made some changes to your forum, and aren't using a default theme like I did during testing, it's possible that not all variables will be inserted. If you're missing a display, you can use the following variables:

<blockquote>{$index_family} // Link to the reservation overview (index)<br />
calls index_family<br /><br />

{$member_profile_family} // Family in profile (member_profile)<br />
calls member_profile_family<br />

{$showthread_family} // Family above post in request area (showthread)<br />
calls showthread_family
</blockquote>

<h1>Template changes</h1>
The following templates are added by this plugin <i>newly</i></i>:

<ul>
<li>family
<li>family_addfamily 	
<li>family_addmember 	
<li>family_claim 	
<li>family_claimed 	
<li>family_claimed_take 	
<li>family_claim_guest 	
<li>family_claim_unplayable 	
<li>family_editfamily 	
<li>family_editmember 	
<li>family_filter_families 	
<li>family_filter_families_bit 	
<li>family_filter_members 	
<li>family_filter_members_bit 	
<li>family_navigation 	
<li>family_navigation_member 	
<li>family_view 	
<li>family_view_generations 	
<li>family_view_generations_member
<li>index_family 
<li>index_family_bit
<li>member_profile_family
<li>showthread_family
</ul>

The following templates are <i>edited</i> by this plugin:
<ul>
<li>index
<li>member_profile
<li>showthread
</ul>

<h1>Recommended plugins</h1>
<a href="https://github.com/MyBBStuff/MyAlerts" target="_blank">MyAlerts</a> by euanT<br />

<h1>Demo</h1>
<i>English screen shots to be added</i>

<center><img src="https://snipboard.io/WQ29lr.jpg" />

<img src="https://snipboard.io/mT3nE9.jpg" />

<img src="https://snipboard.io/WhSvE7.jpg" />

<img src="https://i.snipboard.io/ojrzdE.jpg" />
</center>
