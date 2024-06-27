### Report Types and Their Inputs

1. **get_pageviews_and_sessions_and_visitors_by_channel_by_date_range**
   - `domain`
   - `start_datetime_in_YYYYMMDDHH_format`
   - `end_datetime_in_YYYYMMDDHH_format`
   - `channels`

2. **get_active_cookies_by_date_range**
   - `domain`
   - `start_datetime_in_YYYYMMDDHH_format`
   - `end_datetime_in_YYYYMMDDHH_format`

3. **get_distinct_active_cookies_count_by_date_range**
   - `domain`
   - `start_datetime_in_YYYYMMDDHH_format`
   - `end_datetime_in_YYYYMMDDHH_format`

4. **get_distinct_active_cookies_by_date_range**
   - `domain`
   - `start_datetime_in_YYYYMMDDHH_format`
   - `end_datetime_in_YYYYMMDDHH_format`

5. **get_active_emails_by_date_range**
   - `domain`
   - `start_datetime_in_YYYYMMDDHH_format`
   - `end_datetime_in_YYYYMMDDHH_format`

6. **get_activities_for_cookie**
   - `domain`
   - `cookie_id`

7. **get_ip_addresses_linked_to_cookie**
   - `domain`
   - `cookie_id`

8. **get_emails_for_cookie**
   - `domain`
   - `cookie_id`

9. **get_emails_for_cookies**
   - `domain`
   - `cookie_ids`

10. **get_locations_for_cookie**
    - `domain`
    - `cookie_id`

11. **get_opportunities_linked_to_cookies**
    - `domain`
    - `cookie_ids`

12. **get_everything_linked_to_cookies**
    - `domain`
    - `cookie_ids`

13. **get_predictive_vector_for_cookie_at_specific_hour_in_YYYYMMDDHH_format**
    - `domain`
    - `cookie_id`
    - `specific_hour_in_YYYYMMDDHH_format`

14. **get_predictive_vector_for_cookie_by_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

15. **get_predictive_vector_for_cookies_by_date_range_with_cookie_id_in_output**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

16. **get_next_best_action_and_ads_ids_for_cookies_by_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

17. **get_next_best_action_for_cookie**
    - `domain`
    - `cookie_id`

18. **get_next_best_action_for_email**
    - `domain`
    - `email`

19. **get_activities_for_ip_address**
    - `domain`
    - `ip_address`
    - `cookie_limit_per_ip_address`

20. **get_activities_for_list_of_ip_addresses**
    - `domain`
    - `ip_addresses`
    - `cookie_limit_per_ip_address`

21. **get_cookies_linked_to_ip_address**
    - `domain`
    - `ip_address`

22. **get_emails_for_ip_address**
    - `domain`
    - `ip_address`

23. **get_locations_for_ip_address**
    - `domain`
    - `ip_address`

24. **get_cookies_linked_to_email**
    - `domain`
    - `email`

25. **get_cookies_linked_to_emails**
    - `domain`
    - `emails`

26. **get_ip_address_linked_to_email**
    - `domain`
    - `email`

27. **get_activities_for_email**
    - `domain`
    - `email`

28. **get_activities_for_email_using_ipv4_address_method**
    - `domain`
    - `email`
    - `cookie_limit_per_ip_address`

29. **get_attributions_for_email_before_first_set_identity_event**
    - `domain`
    - `email`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

30. **get_set_identity_events_for_email**
    - `domain`
    - `email`

31. **get_first_set_identity_event_for_email**
    - `domain`
    - `email`

32. **get_crm_opportunities_linked_to_email**
    - `domain`
    - `email`

33. **get_crm_opportunities_linked_to_emails**
    - `domain`
    - `emails`

34. **get_emails_related_by_non_public_domain_for_email**
    - `domain`
    - `email`

35. **get_emails_with_form_submission_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

36. **get_emails_by_first_form_submission_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

37. **get_detailed_attributions_for_emails_by_first_form_submission_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

38. **get_aggregated_attributions_for_emails_by_first_form_submission_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

39. **get_aggregated_attributions_for_emails_by_first_form_submission_date_range_as_time_series_data**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

40. **get_filtered_aggregate_attributions_for_emails_by_first_form_submission_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

41. **get_activities_for_email_before_first_form_submission**
    - `domain`
    - `email`

42. **get_emails_for_non_public_domain**
    - `domain`
    - `email_domain`

43. **get_locations_linked_to_email**
    - `domain`
    - `email`

44. **get_locations_linked_to_array_of_emails**
    - `domain`
    - `emails`

45. **get_locations_linked_to_crm_opportunity**
    - `domain`
    - `opportunity_id`

46. **get_universal_attribution_for_array_of_emails**
    - `domain`
    - `emails`
    - `conversion_timestamp_unix_seconds`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

47. **get_crm_opportunity_schema_for_recent_opportunity**
    - `domain`

48. **get_crm_opportunity**
    - `domain`
    - `opportunity_id`

49. **get_crm_opportunities**
    - `domain`
    - `opportunity_ids`

50. **get_crm_opportunity_with_full_details**
    - `domain`
    - `opportunity_id`
    - `model`
    - `cutoff_in_minutes`

51. **get_crm_opportunities_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

52. **get_crm_opportunities_by_close_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

53. **get_activities_before_created_date_for_crm_opportunity**
    - `domain`
    - `opportunity_id`

54. **get_activities_for_crm_opportunity**
    - `domain`
    - `opportunity_id`

55. **get_attributions_for_crm_opportunity**
    - `domain`
    - `opportunity_id`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

56. **get_detailed_attributions_for_crm_opportunities_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`
    - `crm_object_attributes`

57. **get_aggregated_attributions_for_crm_opportunities_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

58. **get_aggregated_attributions_for_crm_opportunities_by_created_date_as_time_series_data**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

59. **get_custom_filtered_aggregated_attributions_for_crm_opportunities_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`
    - `filter`

60. **get_custom_filtered_attributions_with_details_for_crm_opportunities_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`
    - `filter`

61. **get_detailed_attributions_for_list_of_crm_opportunities**
    - `domain`
    - `list_of_opportunity_ids`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

62. **get_aggregated_attributions_for_list_of_crm_opportunities**
    - `domain`
    - `list_of_opportunity_ids`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

63. **get_aggregated_attributions_for_list_of_crm_opportunities_as_time_series_data**
    - `domain`
    - `list_of_opportunity_ids`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

64. **get_path_attributions_for_crm_opportunity**
    - `domain`
    - `opportunity_id`
    - `cutoff_in_minutes`
    - `channels`

65. **get_path_aggregated_attributions_for_crm_opportunities_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `cutoff_in_minutes`
    - `channels`

66. **get_path_aggregated_attributions_for_crm_opportunities_by_created_date_as_time_series_data**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `cutoff_in_minutes`
    - `channels`

67. **get_path_detailed_attributions_for_list_of_crm_opportunities**
    - `domain`
    - `list_of_opportunity_ids`
    - `cutoff_in_minutes`
    - `channels`

68. **get_aggregated_attributions_for_pageviews_visitors_sessions_emails_and_crm_opportunities_by_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

69. **get_custom_filtered_aggregated_attributions_for_pageviews_visitors_sessions_emails_and_crm_opportunities_by_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`
    - `filter`

70. **get_custom_filtered_detailed_attributions_for_pageviews_visitors_sessions_emails_and_crm_opportunities_by_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`
    - `filter`

71. **get_crm_account_for_crm_opportunity**
    - `domain`
    - `opportunity_id`

72. **get_emails_linked_to_crm_opportunity**
    - `domain`
    - `opportunity_id`

73. **get_crm_lead_schema_for_recent_lead**
    - `domain`

74. **get_crm_leads_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

75. **get_attributions_for_crm_lead**
    - `domain`
    - `id`
    - `model`
    - `cutoff_in_minutes`
    - `channels`
    - `specific_event_attribute`
    - `crm_object_attributes`

76. **get_aggregated_attributions_for_crm_leads_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

77. **get_detailed_attributions_for_crm_leads_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`
    - `crm_object_attributes`

78. **get_crm_contact_schema_for_recent_contact**
    - `domain`

79. **get_crm_contacts_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

80. **get_attributions_for_crm_contact**
    - `domain`
    - `id`
    - `model`
    - `cutoff_in_minutes`
    - `channels`
    - `specific_event_attribute`
    - `crm_object_attributes`

81. **get_aggregated_attributions_for_crm_contacts_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

82. **get_aggregated_attributions_for_crm_contacts_by_created_date_as_time_series_data**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`

83. **get_detailed_attributions_for_crm_contacts_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
    - `channels`
    - `crm_object_attributes`

84. **get_crm_account_schema_for_recent_account**
    - `domain`

85. **get_crm_account**
    - `domain`
    - `account_id`

86. **get_crm_accounts_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

87. **get_cluster_model_for_domain**
    - `domain`

88. **get_cluster_id_for_email**
    - `domain`
    - `email`

89. **get_cluster_id_for_emails_with_form_submission_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

90. **get_lifetime_values_for_email**
    - `domain`
    - `email`

91. **get_lifetime_values_by_crm_opportunities_created_in_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

92. **get_google_ads_clicks_by_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

93. **get_google_ads_clicks_by_ad_and_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

94. **get_google_ads_attributions_for_emails_by_ad_and_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`

95. **get_google_ads_attributions_for_ads_by_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`

96. **get_google_ads_detailed_attributions_for_ads_by_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`

97. **get_google_ad_spend_by_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

98. **get_all_google_ads**
    - `domain`

99. **get_google_ads_details_for_posted_list_of_ad_ids**
    - `domain`
    - `ad_ids`

100. **get_google_ads_details_for_posted_list_of_ad_resource_names**
    - `domain`
    - `ad_resource_names`

101. **get_facebook_ad_spend_by_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

102. **get_facebook_ads_details_for_posted_list_of_ad_ids**
    - `domain`
    - `ad_ids`

103. **get_closed_won_opportunities_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

104. **get_closed_won_opportunities_total_revenue_by_created_date**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`

105. **get_total_ads_attribution_revenue_by_date_range**
    - `domain`
    - `start_datetime_in_YYYYMMDDHH_format`
    - `end_datetime_in_YYYYMMDDHH_format`
    - `model`
    - `cutoff_in_minutes`
