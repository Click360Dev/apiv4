### Report Types and Their Inputs

1. **get_pageviews_and_sessions_and_visitors_by_channel_by_date_range**
   - Retrieves pageviews, sessions, and visitors segmented by specified channels within a date range.
   - Inputs:
     - `domain` (string)
     - `start_datetime_in_YYYYMMDDHH_format` (string)
     - `end_datetime_in_YYYYMMDDHH_format` (string)
     - `channels` (string or array of strings)

2. **get_active_cookies_by_date_range**
   - Retrieves active cookies within a specified date range.
   - Inputs:
     - `domain` (string)
     - `start_datetime_in_YYYYMMDDHH_format` (string)
     - `end_datetime_in_YYYYMMDDHH_format` (string)

3. **get_distinct_active_cookies_count_by_date_range**
   - Retrieves the count of distinct active cookies within a specified date range.
   - Inputs:
     - `domain` (string)
     - `start_datetime_in_YYYYMMDDHH_format` (string)
     - `end_datetime_in_YYYYMMDDHH_format` (string)

4. **get_distinct_active_cookies_by_date_range**
   - Retrieves distinct active cookies within a specified date range.
   - Inputs:
     - `domain` (string)
     - `start_datetime_in_YYYYMMDDHH_format` (string)
     - `end_datetime_in_YYYYMMDDHH_format` (string)

5. **get_active_emails_by_date_range**
   - Retrieves active emails within a specified date range.
   - Inputs:
     - `domain` (string)
     - `start_datetime_in_YYYYMMDDHH_format` (string)
     - `end_datetime_in_YYYYMMDDHH_format` (string)

6. **get_activities_for_cookie**
   - Retrieves activities associated with a specific cookie.
   - Inputs:
     - `domain` (string)
     - `cookie_id` (string)

7. **get_ip_addresses_linked_to_cookie**
   - Retrieves IP addresses linked to a specific cookie.
   - Inputs:
     - `domain` (string)
     - `cookie_id` (string)

8. **get_emails_for_cookie**
   - Retrieves emails linked to a specific cookie.
   - Inputs:
     - `domain` (string)
     - `cookie_id` (string)

9. **get_emails_for_cookies**
   - Retrieves emails linked to an array of cookies.
   - Inputs:
     - `domain` (string)
     - `cookie_ids` (array of strings)

10. **get_locations_for_cookie**
    - Retrieves locations associated with a specific cookie.
    - Inputs:
      - `domain` (string)
      - `cookie_id` (string)

11. **get_opportunities_linked_to_cookies**
    - Retrieves opportunities linked to an array of cookies.
    - Inputs:
      - `domain` (string)
      - `cookie_ids` (array of strings)

12. **get_everything_linked_to_cookies**
    - Retrieves all data linked to an array of cookies.
    - Inputs:
      - `domain` (string)
      - `cookie_ids` (array of strings)

13. **get_predictive_vector_for_cookie_at_specific_hour_in_YYYYMMDDHH_format**
    - Retrieves the predictive vector for a specific cookie at a specified hour.
    - Inputs:
      - `domain` (string)
      - `cookie_id` (string)
      - `specific_hour_in_YYYYMMDDHH_format` (string)

14. **get_predictive_vector_for_cookie_by_date_range**
    - Retrieves the predictive vector for a specific cookie within a date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

15. **get_predictive_vector_for_cookies_by_date_range_with_cookie_id_in_output**
    - Retrieves predictive vectors for multiple cookies within a date range, including cookie IDs in the output.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

16. **get_next_best_action_and_ads_ids_for_cookies_by_date_range**
    - Retrieves the next best action and ad IDs for cookies within a date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

17. **get_next_best_action_for_cookie**
    - Retrieves the next best action for a specific cookie.
    - Inputs:
      - `domain` (string)
      - `cookie_id` (string)

18. **get_next_best_action_for_email**
    - Retrieves the next best action for a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

19. **get_activities_for_ip_address**
    - Retrieves activities associated with a specific IP address, limited by the number of cookies per IP address.
    - Inputs:
      - `domain` (string)
      - `ip_address` (string)
      - `cookie_limit_per_ip_address` (integer)

20. **get_activities_for_list_of_ip_addresses**
    - Retrieves activities associated with a list of IP addresses, limited by the number of cookies per IP address.
    - Inputs:
      - `domain` (string)
      - `ip_addresses` (array of strings)
      - `cookie_limit_per_ip_address` (integer)

21. **get_cookies_linked_to_ip_address**
    - Retrieves cookies linked to a specific IP address.
    - Inputs:
      - `domain` (string)
      - `ip_address` (string)

22. **get_emails_for_ip_address**
    - Retrieves emails linked to a specific IP address.
    - Inputs:
      - `domain` (string)
      - `ip_address` (string)

23. **get_locations_for_ip_address**
    - Retrieves locations associated with a specific IP address.
    - Inputs:
      - `domain` (string)
      - `ip_address` (string)

24. **get_cookies_linked_to_email**
    - Retrieves cookies linked to a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

25. **get_cookies_linked_to_emails**
    - Retrieves cookies linked to an array of emails.
    - Inputs:
      - `domain` (string)
      - `emails` (array of strings)

26. **get_ip_address_linked_to_email**
    - Retrieves IP addresses linked to a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

27. **get_activities_for_email**
    - Retrieves activities associated with a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

28. **get_activities_for_email_using_ipv4_address_method**
    - Retrieves activities for an email using IPv4 address method, limited by the number of cookies per IP address.
    - Inputs:
      - `domain` (string)
      - `email` (string)
      - `cookie_limit_per_ip_address` (integer)

29. **get_attributions_for_email_before_first_set_identity_event**
    - Retrieves attributions for an email before the first set identity event.
    - Inputs:
      - `domain` (string)
      - `email` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

30. **get_set_identity_events_for_email**
    - Retrieves set identity events for a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

31. **get_first_set_identity_event_for_email**
    - Retrieves the first set identity event for a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

32. **get_crm_opportunities_linked_to_email**
    - Retrieves CRM opportunities linked to a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

33. **get_crm_opportunities_linked_to_emails**
    - Retrieves CRM opportunities linked to an array of emails.
    - Inputs:
      - `domain` (string)
      - `emails` (array of strings)

34. **get_emails_related_by_non_public_domain_for_email**
    - Retrieves emails related by non-public domains for a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

35. **get_emails_with_form_submission_date_range**
    - Retrieves emails with form submissions within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

36. **get_emails_by_first_form_submission_date_range**
    - Retrieves emails by their first form submission date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

37. **get_detailed_attributions_for_emails_by_first_form_submission_date_range**
    - Retrieves detailed attributions for emails by their first form submission date within a specified date range.
    - Inputs:


      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

38. **get_aggregated_attributions_for_emails_by_first_form_submission_date_range**
    - Retrieves aggregated attributions for emails by their first form submission date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

39. **get_aggregated_attributions_for_emails_by_first_form_submission_date_range_as_time_series_data**
    - Retrieves aggregated attributions for emails by their first form submission date within a specified date range, presented as time series data.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

40. **get_filtered_aggregate_attributions_for_emails_by_first_form_submission_date_range**
    - Retrieves filtered aggregate attributions for emails by their first form submission date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

41. **get_activities_for_email_before_first_form_submission**
    - Retrieves activities for an email before the first form submission.
    - Inputs:
      - `domain` (string)
      - `email` (string)

42. **get_emails_for_non_public_domain**
    - Retrieves emails for a non-public domain.
    - Inputs:
      - `domain` (string)
      - `email_domain` (string)

43. **get_locations_linked_to_email**
    - Retrieves locations linked to a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

44. **get_locations_linked_to_array_of_emails**
    - Retrieves locations linked to an array of emails.
    - Inputs:
      - `domain` (string)
      - `emails` (array of strings)

45. **get_locations_linked_to_crm_opportunity**
    - Retrieves locations linked to a specific CRM opportunity.
    - Inputs:
      - `domain` (string)
      - `opportunity_id` (string)

46. **get_universal_attribution_for_array_of_emails**
    - Retrieves universal attribution for an array of emails, given a conversion timestamp.
    - Inputs:
      - `domain` (string)
      - `emails` (array of strings)
      - `conversion_timestamp_unix_seconds` (integer)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

47. **get_crm_opportunity_schema_for_recent_opportunity**
    - Retrieves the schema for the most recent CRM opportunity.
    - Inputs:
      - `domain` (string)

48. **get_crm_opportunity**
    - Retrieves a specific CRM opportunity.
    - Inputs:
      - `domain` (string)
      - `opportunity_id` (string)

49. **get_crm_opportunities**
    - Retrieves multiple CRM opportunities.
    - Inputs:
      - `domain` (string)
      - `opportunity_ids` (array of strings)

50. **get_crm_opportunity_with_full_details**
    - Retrieves a specific CRM opportunity with full details.
    - Inputs:
      - `domain` (string)
      - `opportunity_id` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)

51. **get_crm_opportunities_by_created_date**
    - Retrieves CRM opportunities by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

52. **get_crm_opportunities_by_close_date**
    - Retrieves CRM opportunities by their close date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

53. **get_activities_before_created_date_for_crm_opportunity**
    - Retrieves activities before the created date for a specific CRM opportunity.
    - Inputs:
      - `domain` (string)
      - `opportunity_id` (string)

54. **get_activities_for_crm_opportunity**
    - Retrieves activities associated with a specific CRM opportunity.
    - Inputs:
      - `domain` (string)
      - `opportunity_id` (string)

55. **get_attributions_for_crm_opportunity**
    - Retrieves attributions for a specific CRM opportunity.
    - Inputs:
      - `domain` (string)
      - `opportunity_id` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

56. **get_detailed_attributions_for_crm_opportunities_by_created_date**
    - Retrieves detailed attributions for CRM opportunities by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)
      - `crm_object_attributes` (array of strings)

57. **get_aggregated_attributions_for_crm_opportunities_by_created_date**
    - Retrieves aggregated attributions for CRM opportunities by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

58. **get_aggregated_attributions_for_crm_opportunities_by_created_date_as_time_series_data**
    - Retrieves aggregated attributions for CRM opportunities by their created date within a specified date range, presented as time series data.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

59. **get_custom_filtered_aggregated_attributions_for_crm_opportunities_by_created_date**
    - Retrieves custom filtered aggregated attributions for CRM opportunities by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)
      - `filter` (string)

60. **get_custom_filtered_attributions_with_details_for_crm_opportunities_by_created_date**
    - Retrieves custom filtered attributions with details for CRM opportunities by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)
      - `filter` (string)

61. **get_detailed_attributions_for_list_of_crm_opportunities**
    - Retrieves detailed attributions for a list of CRM opportunities.
    - Inputs:
      - `domain` (string)
      - `list_of_opportunity_ids` (array of strings)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

62. **get_aggregated_attributions_for_list_of_crm_opportunities**
    - Retrieves aggregated attributions for a list of CRM opportunities.
    - Inputs:
      - `domain` (string)
      - `list_of_opportunity_ids` (array of strings)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

63. **get_aggregated_attributions_for_list_of_crm_opportunities_as_time_series_data**
    - Retrieves aggregated attributions for a list of CRM opportunities, presented as

 time series data.
    - Inputs:
      - `domain` (string)
      - `list_of_opportunity_ids` (array of strings)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

64. **get_path_attributions_for_crm_opportunity**
    - Retrieves path attributions for a specific CRM opportunity.
    - Inputs:
      - `domain` (string)
      - `opportunity_id` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

65. **get_path_aggregated_attributions_for_crm_opportunities_by_created_date**
    - Retrieves path aggregated attributions for CRM opportunities by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

66. **get_path_aggregated_attributions_for_crm_opportunities_by_created_date_as_time_series_data**
    - Retrieves path aggregated attributions for CRM opportunities by their created date within a specified date range, presented as time series data.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

67. **get_path_detailed_attributions_for_list_of_crm_opportunities**
    - Retrieves path detailed attributions for a list of CRM opportunities.
    - Inputs:
      - `domain` (string)
      - `list_of_opportunity_ids` (array of strings)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

68. **get_aggregated_attributions_for_pageviews_visitors_sessions_emails_and_crm_opportunities_by_date**
    - Retrieves aggregated attributions for pageviews, visitors, sessions, emails, and CRM opportunities by date.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

69. **get_custom_filtered_aggregated_attributions_for_pageviews_visitors_sessions_emails_and_crm_opportunities_by_date**
    - Retrieves custom filtered aggregated attributions for pageviews, visitors, sessions, emails, and CRM opportunities by date.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)
      - `filter` (string)

70. **get_custom_filtered_detailed_attributions_for_pageviews_visitors_sessions_emails_and_crm_opportunities_by_date**
    - Retrieves custom filtered detailed attributions for pageviews, visitors, sessions, emails, and CRM opportunities by date.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)
      - `filter` (string)

71. **get_crm_account_for_crm_opportunity**
    - Retrieves the CRM account associated with a specific CRM opportunity.
    - Inputs:
      - `domain` (string)
      - `opportunity_id` (string)

72. **get_emails_linked_to_crm_opportunity**
    - Retrieves emails linked to a specific CRM opportunity.
    - Inputs:
      - `domain` (string)
      - `opportunity_id` (string)

73. **get_crm_lead_schema_for_recent_lead**
    - Retrieves the schema for the most recent CRM lead.
    - Inputs:
      - `domain` (string)

74. **get_crm_leads_by_created_date**
    - Retrieves CRM leads by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

75. **get_attributions_for_crm_lead**
    - Retrieves attributions for a specific CRM lead.
    - Inputs:
      - `domain` (string)
      - `id` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)
      - `specific_event_attribute` (string)
      - `crm_object_attributes` (array of strings)

76. **get_aggregated_attributions_for_crm_leads_by_created_date**
    - Retrieves aggregated attributions for CRM leads by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

77. **get_detailed_attributions_for_crm_leads_by_created_date**
    - Retrieves detailed attributions for CRM leads by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)
      - `crm_object_attributes` (array of strings)

78. **get_crm_contact_schema_for_recent_contact**
    - Retrieves the schema for the most recent CRM contact.
    - Inputs:
      - `domain` (string)

79. **get_crm_contacts_by_created_date**
    - Retrieves CRM contacts by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

80. **get_attributions_for_crm_contact**
    - Retrieves attributions for a specific CRM contact.
    - Inputs:
      - `domain` (string)
      - `id` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)
      - `specific_event_attribute` (string)
      - `crm_object_attributes` (array of strings)

81. **get_aggregated_attributions_for_crm_contacts_by_created_date**
    - Retrieves aggregated attributions for CRM contacts by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

82. **get_aggregated_attributions_for_crm_contacts_by_created_date_as_time_series_data**
    - Retrieves aggregated attributions for CRM contacts by their created date within a specified date range, presented as time series data.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)

83. **get_detailed_attributions_for_crm_contacts_by_created_date**
    - Retrieves detailed attributions for CRM contacts by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)
      - `channels` (string or array of strings)
      - `crm_object_attributes` (array of strings)

84. **get_crm_account_schema_for_recent_account**
    - Retrieves the schema for the most recent CRM account.
    - Inputs:
      - `domain` (string)

85. **get_crm_account**
    - Retrieves a specific CRM account.
    - Inputs:
      - `domain` (string)
      - `account_id` (string)

86. **get_crm_accounts_by_created_date**
    - Retrieves CRM accounts by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMM

DDHH_format` (string)

87. **get_cluster_model_for_domain**
    - Retrieves the cluster model for a specific domain.
    - Inputs:
      - `domain` (string)

88. **get_cluster_id_for_email**
    - Retrieves the cluster ID for a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

89. **get_cluster_id_for_emails_with_form_submission_date_range**
    - Retrieves cluster IDs for emails with form submissions within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

90. **get_lifetime_values_for_email**
    - Retrieves lifetime values for a specific email.
    - Inputs:
      - `domain` (string)
      - `email` (string)

91. **get_lifetime_values_by_crm_opportunities_created_in_date_range**
    - Retrieves lifetime values for CRM opportunities created within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

92. **get_google_ads_clicks_by_date_range**
    - Retrieves Google Ads clicks within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

93. **get_google_ads_clicks_by_ad_and_date_range**
    - Retrieves Google Ads clicks by ad and within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

94. **get_google_ads_attributions_for_emails_by_ad_and_date_range**
    - Retrieves Google Ads attributions for emails by ad and within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)

95. **get_google_ads_attributions_for_ads_by_date_range**
    - Retrieves Google Ads attributions for ads within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)

96. **get_google_ads_detailed_attributions_for_ads_by_date_range**
    - Retrieves detailed Google Ads attributions for ads within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)

97. **get_google_ad_spend_by_date_range**
    - Retrieves Google Ad spend within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

98. **get_all_google_ads**
    - Retrieves all Google Ads for a specific domain.
    - Inputs:
      - `domain` (string)

99. **get_google_ads_details_for_posted_list_of_ad_ids**
    - Retrieves details for a posted list of Google Ad IDs.
    - Inputs:
      - `domain` (string)
      - `ad_ids` (array of strings)

100. **get_google_ads_details_for_posted_list_of_ad_resource_names**
    - Retrieves details for a posted list of Google Ad resource names.
    - Inputs:
      - `domain` (string)
      - `ad_resource_names` (array of strings)

101. **get_facebook_ad_spend_by_date_range**
    - Retrieves Facebook Ad spend within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

102. **get_facebook_ads_details_for_posted_list_of_ad_ids**
    - Retrieves details for a posted list of Facebook Ad IDs.
    - Inputs:
      - `domain` (string)
      - `ad_ids` (array of strings)

103. **get_closed_won_opportunities_by_created_date**
    - Retrieves closed won opportunities by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

104. **get_closed_won_opportunities_total_revenue_by_created_date**
    - Retrieves total revenue of closed won opportunities by their created date within a specified date range.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)

105. **get_total_ads_attribution_revenue_by_date_range**
    - Retrieves total ads attribution revenue by date range, using a specified model and cutoff.
    - Inputs:
      - `domain` (string)
      - `start_datetime_in_YYYYMMDDHH_format` (string)
      - `end_datetime_in_YYYYMMDDHH_format` (string)
      - `model` (string)
      - `cutoff_in_minutes` (integer)

### Attribution Models

The `model` parameter can be one of the following values:

- **equal**: Distributes the credit for a conversion equally across all touchpoints in the customer journey.
- **firsttouch**: Assigns 100% of the credit for a conversion to the first touchpoint in the customer journey.
- **lasttouch**: Assigns 100% of the credit for a conversion to the last touchpoint in the customer journey.
- **firstandlasttouch**: Splits the credit for a conversion between the first and the last touchpoints in the customer journey.
- **any**: Assigns credit to any touchpoint in the customer journey that contributed to the conversion.
- **path**: Shows the path for the conversion, detailing all the touchpoints in the customer journey.

### Channels

The `channels` parameter can include:
(1) any Query String parameter, and 
(2) any of the standard channels, which include:
- `source`
- `medium`
- `campaign`
- `lastreferrerdomain`
- `content`
- `term`
- `browsername`
- `browserversion`
- `browserosversion`
- `browserplatformtype`
- `browserplatformvendor`
- `postalcode`
- `country`
- `region`
- `city`
- `ad_id`
- `attribution_date`
- `attribution_year`
- `attribution_month`
- `attribution_quarter`
- `attribution_week`
- `attribution_quarter_of_year`
- `attribution_month_of_year`
- `attribution_day_of_year`
- `attribution_day_of_month`
- `attribution_week_of_year`
- `attribution_day_of_week`
