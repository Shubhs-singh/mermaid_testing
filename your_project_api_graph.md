```mermaid
graph TD
    node_7521111["🔧 extract_text_from_pdf"]
    style node_7521111 fill:#b3d9ff
    node_568999["🔧 to_lowercase"]
    style node_568999 fill:#b3d9ff
    node_2571628["🔧 find_word"]
    style node_2571628 fill:#b3d9ff
    node_930312["🔧 classify_pages"]
    style node_930312 fill:#b3d9ff
    node_116845["🔧 split_pdf_by_dict"]
    style node_116845 fill:#b3d9ff
    node_9701828["🔧 pdf_to_images"]
    style node_9701828 fill:#b3d9ff
    node_6149880["🌐 unknown.get_pixmap"]
    style node_6149880 fill:#b3ffb3
    node_2948579["🔧 pdf_bytes_to_images"]
    style node_2948579 fill:#b3d9ff
    node_926323["🔧 detect_logo_regions"]
    style node_926323 fill:#b3d9ff
    node_7800899["🔧 crop_logo_regions"]
    style node_7800899 fill:#b3d9ff
    node_14743362["🔧 extract_text_from_logos"]
    style node_14743362 fill:#b3d9ff
    node_7812467["🔧 get_hsn_from_description"]
    style node_7812467 fill:#b3d9ff
    node_15244654["🔧 get_hsn_code_from_inv_text"]
    style node_15244654 fill:#b3d9ff
    node_7803633["🔧 extract_hsn_from_plain_text"]
    style node_7803633 fill:#b3d9ff
    node_15819702["🔧 setup_model"]
    style node_15819702 fill:#b3d9ff
    node_6469533["🌐 os.getenv"]
    style node_6469533 fill:#b3ffb3
    node_4527510["🔧 rename_df_columns"]
    style node_4527510 fill:#b3d9ff
    node_11606657["🔧 get_pdf_files"]
    style node_11606657 fill:#b3d9ff
    node_3359937["🔧 get_invoice_data_using_pre_built_invoice"]
    style node_3359937 fill:#b3d9ff
    node_7901486["🔧 get_max_item_amt_grpd_inv_no_date"]
    style node_7901486 fill:#b3d9ff
    node_15076349["🌐 checklist_json.get"]
    style node_15076349 fill:#b3ffb3
    node_2268102["🌐 unknown.get"]
    style node_2268102 fill:#b3ffb3
    node_3044285["🌐 standard_data.get"]
    style node_3044285 fill:#b3ffb3
    node_16665068["🌐 gst.get_customer_gst_using_regex"]
    style node_16665068 fill:#b3ffb3
    node_2208030["🌐 po.get_po_number_based_on_checklist"]
    style node_2208030 fill:#b3ffb3
    node_15155677["🌐 gst.get_vendor_gst_based_on_checklist"]
    style node_15155677 fill:#b3ffb3
    node_6715875["🌐 item_data.get"]
    style node_6715875 fill:#b3ffb3
    node_11357158["🌐 hsn.get_hsn_from_description"]
    style node_11357158 fill:#b3ffb3
    node_9508948["🔧 get_std_fields_for_max_gross_amount"]
    style node_9508948 fill:#b3d9ff
    node_11211656["🌐 hsn.get_hsn_code_from_inv_text"]
    style node_11211656 fill:#b3ffb3
    node_1747970["🔧 process_in_batches"]
    style node_1747970 fill:#b3d9ff
    node_15201497["🔧 get_hsn_tds_batch"]
    style node_15201497 fill:#b3d9ff
    node_13210312["🔧 classify_expense_gpt"]
    style node_13210312 fill:#b3d9ff
    node_276053["🔧 map_results_to_dataframe"]
    style node_276053 fill:#b3d9ff
    node_15052965["🔧 get_checklist_specific_fields"]
    style node_15052965 fill:#b3d9ff
    node_5035752["🔧 filter_invoices_based_on_checklist_fields"]
    style node_5035752 fill:#b3d9ff
    node_13051912["🌐 json_data.get"]
    style node_13051912 fill:#b3ffb3
    node_9667513["🔧 get_gst_fields"]
    style node_9667513 fill:#b3d9ff
    node_403024["🌐 get_standard_gst_fields"]
    style node_403024 fill:#b3ffb3
    node_11071751["🔧 map_columns_with_gpt"]
    style node_11071751 fill:#b3d9ff
    node_6665005["🔧 extract_and_merge_dataframes"]
    style node_6665005 fill:#b3d9ff
    node_16730912["🔧 preprocess_image"]
    style node_16730912 fill:#b3d9ff
    node_9254960["🔧 extract_irn_from_pdf"]
    style node_9254960 fill:#b3d9ff
    node_6213332["🌐 page.get"]
    style node_6213332 fill:#b3ffb3
    node_7305430["🔧 check_if_rcm_tag_available_in_invoice"]
    style node_7305430 fill:#b3d9ff
    node_1669711["🔧 get_doc_category"]
    style node_1669711 fill:#b3d9ff
    node_16193406["🌐 pdf_bytes.getvalue"]
    style node_16193406 fill:#b3ffb3
    node_4274051["🌐 get_access_token"]
    style node_4274051 fill:#b3ffb3
    node_11048294["🌐 requests.post"]
    style node_11048294 fill:#b3ffb3
    node_7848838["🌐 fetch_supplier_name"]
    style node_7848838 fill:#b3ffb3
    node_4323348["🌐 requests.get"]
    style node_4323348 fill:#b3ffb3
    node_1860581["🌐 response_data.get"]
    style node_1860581 fill:#b3ffb3
    node_15181552["🔧 add_supplier_names_column"]
    style node_15181552 fill:#b3d9ff
    node_3121755["🔧 fetch_invoice_details_using_qr_string"]
    style node_3121755 fill:#b3d9ff
    node_14723950["🔧 get_name"]
    style node_14723950 fill:#b3d9ff
    node_775105["🔧 correct_gstin_format"]
    style node_775105 fill:#b3d9ff
    node_14337381["🔧 is_valid_gstin"]
    style node_14337381 fill:#b3d9ff
    node_5318938["🔧 validate_gstin_checksum"]
    style node_5318938 fill:#b3d9ff
    node_5239206["🔧 get_vendor_gst_based_on_checklist"]
    style node_5239206 fill:#b3d9ff
    node_607557["🔧 get_customer_gst_using_regex"]
    style node_607557 fill:#b3d9ff
    node_6069674["🔧 get_po_number_based_on_checklist"]
    style node_6069674 fill:#b3d9ff
    node_11229987["🔧 validate_po_based_on_file_name"]
    style node_11229987 fill:#b3d9ff
    node_15663455["🔧 clean_and_convert_series"]
    style node_15663455 fill:#b3d9ff
    node_607681["🔧 process_invoice_amounts"]
    style node_607681 fill:#b3d9ff
    node_1942760["🔧 get_auth_token"]
    style node_1942760 fill:#b3d9ff
    node_8809595["🔧 get_invoice_details"]
    style node_8809595 fill:#b3d9ff
    node_568999 -.-> node_2571628
    node_930312 --> node_568999
    node_930312 --> node_2571628
    node_9701828 ==> node_6149880
    node_2948579 ==> node_6149880
    node_15244654 --> node_7803633
    node_15819702 ==> node_6469533
    node_3359937 --> node_7901486
    node_3359937 ==> node_15076349
    node_3359937 ==> node_2268102
    node_3359937 ==> node_3044285
    node_3359937 ==> node_16665068
    node_3359937 ==> node_2208030
    node_3359937 ==> node_15155677
    node_3359937 ==> node_6715875
    node_3359937 ==> node_11357158
    node_3359937 --> node_9508948
    node_3359937 ==> node_11211656
    node_7901486 -.-> node_7901486
    node_7901486 -.-> node_9508948
    node_1747970 --> node_15201497
    node_1747970 --> node_13210312
    node_5035752 ==> node_13051912
    node_9667513 --> node_6665005
    node_403024 --> node_11071751
    node_6665005 --> node_403024
    node_9254960 ==> node_6213332
    node_7305430 ==> node_6213332
    node_1669711 ==> node_16193406
    node_1669711 --> node_16730912
    node_4274051 ==> node_11048294
    node_4274051 ==> node_2268102
    node_4274051 -.-> node_7848838
    node_7848838 ==> node_4323348
    node_7848838 ==> node_2268102
    node_7848838 ==> node_1860581
    node_15181552 --> node_4274051
    node_15181552 --> node_7848838
    node_3121755 ==> node_11048294
    node_3121755 ==> node_1860581
    node_14723950 --> node_4274051
    node_14723950 --> node_7848838
    node_14337381 --> node_5318938
    node_5239206 --> node_14337381
    node_607557 --> node_14337381
    node_607681 --> node_15663455
    node_1942760 ==> node_11048294
    node_1942760 ==> node_2268102
    node_8809595 ==> node_11048294
```