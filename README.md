```
     ██╗ ██████╗  ██████╗ ███╗   ███╗██╗      █████╗ 
     ██║██╔═══██╗██╔═══██╗████╗ ████║██║     ██╔══██╗
     ██║██║   ██║██║   ██║██╔████╔██║██║     ███████║
██   ██║██║   ██║██║   ██║██║╚██╔╝██║██║     ██╔══██║
╚█████╔╝╚██████╔╝╚██████╔╝██║ ╚═╝ ██║███████╗██║  ██║
 ╚════╝  ╚═════╝  ╚═════╝ ╚═╝     ╚═╝╚══════╝╚═╝  ╚═╝
██████╗  ██████╗ ██╗    ██╗███████╗██████╗ ███████╗  
██╔══██╗██╔═══██╗██║    ██║██╔════╝██╔══██╗██╔════╝  
██████╔╝██║   ██║██║ █╗ ██║█████╗  ██████╔╝███████╗  
██╔═══╝ ██║   ██║██║███╗██║██╔══╝  ██╔══██╗╚════██║  
██║     ╚██████╔╝╚███╔███╔╝███████╗██║  ██║███████║  
╚═╝      ╚═════╝  ╚══╝╚══╝ ╚══════╝╚═╝  ╚═╝╚══════╝
```

### What is JCB Joomla Powers?
The Joomla Component Builder (JCB) Joomla Power features are designed to enhance JCB's functionality and streamline the development process. The Joomla powers enable developers to effectively leverage Joomla classes in their custom code without needing to manually add the `use` statements for those classes to the file headers. JCB automatically updates these `use` statements in the necessary headers when it detects a Joomla power key in the custom code.



By doing this, we can control the `use` statements dynamically from a central point. This is particularly beneficial when transitioning from Joomla 3 to Joomla 4, as it allows us to seamlessly switch from certain classes to their respective Joomla framework classes and vice versa. Maintaining these `use` statements in the Joomla Power area ensures that JCB handles the inclusion and updating of class names to prevent conflicts with other classes.



This approach is convenient and allows developers to focus on the bespoke parts of their application logic without worrying about class declarations.


This repository contains an index (see below) of all the Joomla! Powers within the JCB core GUI. These Joomla! Powers are automatically added to the repository by our maintainers, ensuring a well-organized and accessible collection of Joomla Classes are maintained.

# Index of Joomla! Powers

 - **JClassLoader** | [Details](src/0e589f1c-7288-4c5e-ada0-3b8593875de0) | [Settings](src/0e589f1c-7288-4c5e-ada0-3b8593875de0/item.json) | JPK: `Joomla---0e589f1c_7288_4c5e_ada0_3b8593875de0---Power`
 - **JDatabaseDriver** | [Details](src/ec78bf74-f80c-42df-85cc-6c1ecd2417fc) | [Settings](src/ec78bf74-f80c-42df-85cc-6c1ecd2417fc/item.json) | JPK: `Joomla---ec78bf74_f80c_42df_85cc_6c1ecd2417fc---Power`
 - **JDatabaseDriverMysqli** | [Details](src/c8bd9af6-7821-4a12-b7bf-f04b492e03c3) | [Settings](src/c8bd9af6-7821-4a12-b7bf-f04b492e03c3/item.json) | JPK: `Joomla---c8bd9af6_7821_4a12_b7bf_f04b492e03c3---Power`
 - **JDatabaseDriverPdo** | [Details](src/33aed640-4fd5-4b93-b5ee-7bc98499e97a) | [Settings](src/33aed640-4fd5-4b93-b5ee-7bc98499e97a/item.json) | JPK: `Joomla---33aed640_4fd5_4b93_b5ee_7bc98499e97a---Power`
 - **JDatabaseDriverPdomysql** | [Details](src/40c148a2-0fb1-424e-b5f9-f9edf1130f85) | [Settings](src/40c148a2-0fb1-424e-b5f9-f9edf1130f85/item.json) | JPK: `Joomla---40c148a2_0fb1_424e_b5f9_f9edf1130f85---Power`
 - **JDatabaseDriverPgsql** | [Details](src/3a7db958-21dd-4fd6-acca-077be8dcb534) | [Settings](src/3a7db958-21dd-4fd6-acca-077be8dcb534/item.json) | JPK: `Joomla---3a7db958_21dd_4fd6_acca_077be8dcb534---Power`
 - **JDatabaseDriverSqlazure** | [Details](src/52e8fced-b8a6-4ab8-b249-55acd61504c2) | [Settings](src/52e8fced-b8a6-4ab8-b249-55acd61504c2/item.json) | JPK: `Joomla---52e8fced_b8a6_4ab8_b249_55acd61504c2---Power`
 - **JDatabaseDriverSqlite** | [Details](src/325ac31d-c4bc-4f83-88e0-0cd4cd233f7f) | [Settings](src/325ac31d-c4bc-4f83-88e0-0cd4cd233f7f/item.json) | JPK: `Joomla---325ac31d_c4bc_4f83_88e0_0cd4cd233f7f---Power`
 - **JDatabaseDriverSqlsrv** | [Details](src/76965fed-18ce-41da-b89c-43bd5fd40f92) | [Settings](src/76965fed-18ce-41da-b89c-43bd5fd40f92/item.json) | JPK: `Joomla---76965fed_18ce_41da_b89c_43bd5fd40f92---Power`
 - **JDatabaseExceptionConnecting** | [Details](src/4ea4e196-9c69-4eb1-ae7e-d09d8b1a9bed) | [Settings](src/4ea4e196-9c69-4eb1-ae7e-d09d8b1a9bed/item.json) | JPK: `Joomla---4ea4e196_9c69_4eb1_ae7e_d09d8b1a9bed---Power`
 - **JDatabaseExceptionExecuting** | [Details](src/54c9fc90-5f76-42fa-bf63-d3bfa56c3ad0) | [Settings](src/54c9fc90-5f76-42fa-bf63-d3bfa56c3ad0/item.json) | JPK: `Joomla---54c9fc90_5f76_42fa_bf63_d3bfa56c3ad0---Power`
 - **JDatabaseExceptionUnsupported** | [Details](src/62f11ab3-7903-4e1d-b899-cf6df3b32467) | [Settings](src/62f11ab3-7903-4e1d-b899-cf6df3b32467/item.json) | JPK: `Joomla---62f11ab3_7903_4e1d_b899_cf6df3b32467---Power`
 - **JDatabaseExporter** | [Details](src/ed39669e-c163-43c7-b942-2aa16f0bcebd) | [Settings](src/ed39669e-c163-43c7-b942-2aa16f0bcebd/item.json) | JPK: `Joomla---ed39669e_c163_43c7_b942_2aa16f0bcebd---Power`
 - **JDatabaseExporterMysqli** | [Details](src/a5bade51-4131-40db-9dbe-0fd81ff8c627) | [Settings](src/a5bade51-4131-40db-9dbe-0fd81ff8c627/item.json) | JPK: `Joomla---a5bade51_4131_40db_9dbe_0fd81ff8c627---Power`
 - **JDatabaseExporterPdomysql** | [Details](src/30864f36-704e-4d28-a1b5-49d24b2ffe5e) | [Settings](src/30864f36-704e-4d28-a1b5-49d24b2ffe5e/item.json) | JPK: `Joomla---30864f36_704e_4d28_a1b5_49d24b2ffe5e---Power`
 - **JDatabaseExporterPgsql** | [Details](src/3ae5f3d6-5916-4319-983f-193654d9a821) | [Settings](src/3ae5f3d6-5916-4319-983f-193654d9a821/item.json) | JPK: `Joomla---3ae5f3d6_5916_4319_983f_193654d9a821---Power`
 - **JDatabaseFactory** | [Details](src/fe666da1-eebe-41e0-9b05-f2b747d2bc8f) | [Settings](src/fe666da1-eebe-41e0-9b05-f2b747d2bc8f/item.json) | JPK: `Joomla---fe666da1_eebe_41e0_9b05_f2b747d2bc8f---Power`
 - **JDatabaseImporter** | [Details](src/837bb77a-c85b-480d-ae8c-93c95e9c34d0) | [Settings](src/837bb77a-c85b-480d-ae8c-93c95e9c34d0/item.json) | JPK: `Joomla---837bb77a_c85b_480d_ae8c_93c95e9c34d0---Power`
 - **JDatabaseImporterMysqli** | [Details](src/cc6e5cc3-19c8-4cab-b10b-9825aa142ead) | [Settings](src/cc6e5cc3-19c8-4cab-b10b-9825aa142ead/item.json) | JPK: `Joomla---cc6e5cc3_19c8_4cab_b10b_9825aa142ead---Power`
 - **JDatabaseImporterPdomysql** | [Details](src/4481898b-7cdc-496a-b717-a245d494de64) | [Settings](src/4481898b-7cdc-496a-b717-a245d494de64/item.json) | JPK: `Joomla---4481898b_7cdc_496a_b717_a245d494de64---Power`
 - **JDatabaseImporterPgsql** | [Details](src/84f05d10-31ed-44ce-bffe-04d7c12c350a) | [Settings](src/84f05d10-31ed-44ce-bffe-04d7c12c350a/item.json) | JPK: `Joomla---84f05d10_31ed_44ce_bffe_04d7c12c350a---Power`
 - **JDatabaseInterface** | [Details](src/7bd29d76-73c9-4c07-a5da-4f7a32aff78f) | [Settings](src/7bd29d76-73c9-4c07-a5da-4f7a32aff78f/item.json) | JPK: `Joomla---7bd29d76_73c9_4c07_a5da_4f7a32aff78f---Power`
 - **JDatabaseIterator** | [Details](src/f9c17662-8434-4819-85bd-e62c59c8ce25) | [Settings](src/f9c17662-8434-4819-85bd-e62c59c8ce25/item.json) | JPK: `Joomla---f9c17662_8434_4819_85bd_e62c59c8ce25---Power`
 - **JDatabaseQuery** | [Details](src/cf86ed0d-bbe6-4451-aeb8-c63ee4d0fc14) | [Settings](src/cf86ed0d-bbe6-4451-aeb8-c63ee4d0fc14/item.json) | JPK: `Joomla---cf86ed0d_bbe6_4451_aeb8_c63ee4d0fc14---Power`
 - **JDatabaseQueryElement** | [Details](src/e5a0df6b-c0a7-485e-acee-091d8c610fc1) | [Settings](src/e5a0df6b-c0a7-485e-acee-091d8c610fc1/item.json) | JPK: `Joomla---e5a0df6b_c0a7_485e_acee_091d8c610fc1---Power`
 - **JDatabaseQueryLimitable** | [Details](src/e23ccf34-2cf2-4ae7-8a73-adb2fc1d2493) | [Settings](src/e23ccf34-2cf2-4ae7-8a73-adb2fc1d2493/item.json) | JPK: `Joomla---e23ccf34_2cf2_4ae7_8a73_adb2fc1d2493---Power`
 - **JDatabaseQueryMysqli** | [Details](src/ecacda91-6902-4c19-9cbd-101f8faacc1c) | [Settings](src/ecacda91-6902-4c19-9cbd-101f8faacc1c/item.json) | JPK: `Joomla---ecacda91_6902_4c19_9cbd_101f8faacc1c---Power`
 - **JDatabaseQueryPdo** | [Details](src/943e39bf-87a2-45fa-9fc6-07d784212358) | [Settings](src/943e39bf-87a2-45fa-9fc6-07d784212358/item.json) | JPK: `Joomla---943e39bf_87a2_45fa_9fc6_07d784212358---Power`
 - **JDatabaseQueryPdomysql** | [Details](src/52cd1c83-a2ec-47c6-9c3c-7d316165addc) | [Settings](src/52cd1c83-a2ec-47c6-9c3c-7d316165addc/item.json) | JPK: `Joomla---52cd1c83_a2ec_47c6_9c3c_7d316165addc---Power`
 - **JDatabaseQueryPgsql** | [Details](src/ec48cc53-4a90-47a4-bb8f-6b496cfacf43) | [Settings](src/ec48cc53-4a90-47a4-bb8f-6b496cfacf43/item.json) | JPK: `Joomla---ec48cc53_4a90_47a4_bb8f_6b496cfacf43---Power`
 - **JDatabaseQueryPreparable** | [Details](src/f46f02b4-e39e-40c3-ba1a-c590f52ea467) | [Settings](src/f46f02b4-e39e-40c3-ba1a-c590f52ea467/item.json) | JPK: `Joomla---f46f02b4_e39e_40c3_ba1a_c590f52ea467---Power`
 - **JDatabaseQuerySqlazure** | [Details](src/7d4657c9-5896-410f-9c13-7348588018e8) | [Settings](src/7d4657c9-5896-410f-9c13-7348588018e8/item.json) | JPK: `Joomla---7d4657c9_5896_410f_9c13_7348588018e8---Power`
 - **JDatabaseQuerySqlite** | [Details](src/3e3c8caa-822e-4f9f-b395-a14a3f6f31e4) | [Settings](src/3e3c8caa-822e-4f9f-b395-a14a3f6f31e4/item.json) | JPK: `Joomla---3e3c8caa_822e_4f9f_b395_a14a3f6f31e4---Power`
 - **JDatabaseQuerySqlsrv** | [Details](src/5e22cd09-33e9-43d7-8cfa-3225822296a1) | [Settings](src/5e22cd09-33e9-43d7-8cfa-3225822296a1/item.json) | JPK: `Joomla---5e22cd09_33e9_43d7_8cfa_3225822296a1---Power`
 - **JFormFieldColor** | [Details](src/521a1a08-97b5-46fa-adf1-49a2295ab883) | [Settings](src/521a1a08-97b5-46fa-adf1-49a2295ab883/item.json) | JPK: `Joomla---521a1a08_97b5_46fa_adf1_49a2295ab883---Power`
 - **JFormFieldCombo** | [Details](src/55be30ee-0823-480a-aba8-e0bc2cb64503) | [Settings](src/55be30ee-0823-480a-aba8-e0bc2cb64503/item.json) | JPK: `Joomla---55be30ee_0823_480a_aba8_e0bc2cb64503---Power`
 - **JFormFieldComponentlayout** | [Details](src/cf5e4e33-3822-46fa-bd59-d8b8dd84fe0a) | [Settings](src/cf5e4e33-3822-46fa-bd59-d8b8dd84fe0a/item.json) | JPK: `Joomla---cf5e4e33_3822_46fa_bd59_d8b8dd84fe0a---Power`
 - **JFormFieldComponents** | [Details](src/3582a327-292f-48a4-b3e1-970bbc078411) | [Settings](src/3582a327-292f-48a4-b3e1-970bbc078411/item.json) | JPK: `Joomla---3582a327_292f_48a4_b3e1_970bbc078411---Power`
 - **JFormFieldDatabaseConnection** | [Details](src/e42ffd96-0c63-43c3-9d96-f40ba67628c0) | [Settings](src/e42ffd96-0c63-43c3-9d96-f40ba67628c0/item.json) | JPK: `Joomla---e42ffd96_0c63_43c3_9d96_f40ba67628c0---Power`
 - **JFormFieldEMail** | [Details](src/8024b772-6bfe-47cf-b776-39c883789e48) | [Settings](src/8024b772-6bfe-47cf-b776-39c883789e48/item.json) | JPK: `Joomla---8024b772_6bfe_47cf_b776_39c883789e48---Power`
 - **JFormFieldFile** | [Details](src/1ce01a05-7010-427d-a333-37dcd3947f56) | [Settings](src/1ce01a05-7010-427d-a333-37dcd3947f56/item.json) | JPK: `Joomla---1ce01a05_7010_427d_a333_37dcd3947f56---Power`
 - **JFormFieldFileList** | [Details](src/ff395590-ed93-4e39-8636-c9084325de96) | [Settings](src/ff395590-ed93-4e39-8636-c9084325de96/item.json) | JPK: `Joomla---ff395590_ed93_4e39_8636_c9084325de96---Power`
 - **JFormFieldFolderList** | [Details](src/c5e03fd6-4919-4463-9a86-82033763d649) | [Settings](src/c5e03fd6-4919-4463-9a86-82033763d649/item.json) | JPK: `Joomla---c5e03fd6_4919_4463_9a86_82033763d649---Power`
 - **JFormFieldGroupedList** | [Details](src/92eb5c12-48f4-4b2c-8f2f-08f95019ecc7) | [Settings](src/92eb5c12-48f4-4b2c-8f2f-08f95019ecc7/item.json) | JPK: `Joomla---92eb5c12_48f4_4b2c_8f2f_08f95019ecc7---Power`
 - **JFormFieldHidden** | [Details](src/fe2d12c0-a6e3-4a85-b2e6-1e792d2ed774) | [Settings](src/fe2d12c0-a6e3-4a85-b2e6-1e792d2ed774/item.json) | JPK: `Joomla---fe2d12c0_a6e3_4a85_b2e6_1e792d2ed774---Power`
 - **JFormFieldImageList** | [Details](src/1e403041-66cc-424b-a435-b82538036a44) | [Settings](src/1e403041-66cc-424b-a435-b82538036a44/item.json) | JPK: `Joomla---1e403041_66cc_424b_a435_b82538036a44---Power`
 - **JFormFieldInteger** | [Details](src/ccb4a7a6-67f6-4db5-b89c-324bfbed3981) | [Settings](src/ccb4a7a6-67f6-4db5-b89c-324bfbed3981/item.json) | JPK: `Joomla---ccb4a7a6_67f6_4db5_b89c_324bfbed3981---Power`
 - **JFormFieldLanguage** | [Details](src/fa54b2bf-61fd-401e-8e89-96adb3d919bf) | [Settings](src/fa54b2bf-61fd-401e-8e89-96adb3d919bf/item.json) | JPK: `Joomla---fa54b2bf_61fd_401e_8e89_96adb3d919bf---Power`
 - **JFormFieldList** | [Details](src/960bb57d-eafc-4aa8-830d-f74898b7a546) | [Settings](src/960bb57d-eafc-4aa8-830d-f74898b7a546/item.json) | JPK: `Joomla---960bb57d_eafc_4aa8_830d_f74898b7a546---Power`
 - **JFormFieldMeter** | [Details](src/d9b4d9a1-f6e5-46ef-ac46-6f91969a4139) | [Settings](src/d9b4d9a1-f6e5-46ef-ac46-6f91969a4139/item.json) | JPK: `Joomla---d9b4d9a1_f6e5_46ef_ac46_6f91969a4139---Power`
 - **JFormFieldModulelayout** | [Details](src/ab56b96f-8904-4d0e-af60-29f8b4bc6252) | [Settings](src/ab56b96f-8904-4d0e-af60-29f8b4bc6252/item.json) | JPK: `Joomla---ab56b96f_8904_4d0e_af60_29f8b4bc6252---Power`
 - **JFormFieldNote** | [Details](src/4c4bc84e-e324-4064-83e5-282d854d3a22) | [Settings](src/4c4bc84e-e324-4064-83e5-282d854d3a22/item.json) | JPK: `Joomla---4c4bc84e_e324_4064_83e5_282d854d3a22---Power`
 - **JFormFieldNumber** | [Details](src/e1659b22-2f96-49fa-a26f-84dab3001abe) | [Settings](src/e1659b22-2f96-49fa-a26f-84dab3001abe/item.json) | JPK: `Joomla---e1659b22_2f96_49fa_a26f_84dab3001abe---Power`
 - **JFormFieldPassword** | [Details](src/b190bdbe-1868-4c7c-bbb8-af66e1d78191) | [Settings](src/b190bdbe-1868-4c7c-bbb8-af66e1d78191/item.json) | JPK: `Joomla---b190bdbe_1868_4c7c_bbb8_af66e1d78191---Power`
 - **JFormFieldPlugins** | [Details](src/d88ab2ea-70d2-4da5-8a8f-44adc308f223) | [Settings](src/d88ab2ea-70d2-4da5-8a8f-44adc308f223/item.json) | JPK: `Joomla---d88ab2ea_70d2_4da5_8a8f_44adc308f223---Power`
 - **JFormFieldPredefinedList** | [Details](src/8d5d180e-257e-4c57-8205-6c04771f6999) | [Settings](src/8d5d180e-257e-4c57-8205-6c04771f6999/item.json) | JPK: `Joomla---8d5d180e_257e_4c57_8205_6c04771f6999---Power`
 - **JFormFieldRadio** | [Details](src/0b2a2152-d48a-490d-a147-5dbb194fe2af) | [Settings](src/0b2a2152-d48a-490d-a147-5dbb194fe2af/item.json) | JPK: `Joomla---0b2a2152_d48a_490d_a147_5dbb194fe2af---Power`
 - **JFormFieldRange** | [Details](src/4abb8168-ee77-42c0-8cb4-9d7c1ec85ce6) | [Settings](src/4abb8168-ee77-42c0-8cb4-9d7c1ec85ce6/item.json) | JPK: `Joomla---4abb8168_ee77_42c0_8cb4_9d7c1ec85ce6---Power`
 - **JFormFieldRules** | [Details](src/aa4a472d-3791-48a8-bb28-6c335a858adc) | [Settings](src/aa4a472d-3791-48a8-bb28-6c335a858adc/item.json) | JPK: `Joomla---aa4a472d_3791_48a8_bb28_6c335a858adc---Power`
 - **JFormFieldSQL** | [Details](src/1afe394e-e066-4f96-98c0-d78f38d66638) | [Settings](src/1afe394e-e066-4f96-98c0-d78f38d66638/item.json) | JPK: `Joomla---1afe394e_e066_4f96_98c0_d78f38d66638---Power`
 - **JFormFieldSessionHandler** | [Details](src/81edbf8f-308c-40c3-95e0-6026815e6ccb) | [Settings](src/81edbf8f-308c-40c3-95e0-6026815e6ccb/item.json) | JPK: `Joomla---81edbf8f_308c_40c3_95e0_6026815e6ccb---Power`
 - **JFormFieldSpacer** | [Details](src/b6059797-0263-4f94-b313-81f76a80e1cb) | [Settings](src/b6059797-0263-4f94-b313-81f76a80e1cb/item.json) | JPK: `Joomla---b6059797_0263_4f94_b313_81f76a80e1cb---Power`
 - **JFormFieldSubform** | [Details](src/b3319bad-a2b4-4762-af28-7942bea822bd) | [Settings](src/b3319bad-a2b4-4762-af28-7942bea822bd/item.json) | JPK: `Joomla---b3319bad_a2b4_4762_af28_7942bea822bd---Power`
 - **JFormFieldTel** | [Details](src/62abd5ac-95d8-4263-abd4-29aba234bed9) | [Settings](src/62abd5ac-95d8-4263-abd4-29aba234bed9/item.json) | JPK: `Joomla---62abd5ac_95d8_4263_abd4_29aba234bed9---Power`
 - **JFormFieldText** | [Details](src/d977aed1-4935-4e7e-982c-399b5c7bdb9e) | [Settings](src/d977aed1-4935-4e7e-982c-399b5c7bdb9e/item.json) | JPK: `Joomla---d977aed1_4935_4e7e_982c_399b5c7bdb9e---Power`
 - **JFormFieldTextarea** | [Details](src/305617a7-c828-4a8c-ac77-8c88f0535549) | [Settings](src/305617a7-c828-4a8c-ac77-8c88f0535549/item.json) | JPK: `Joomla---305617a7_c828_4a8c_ac77_8c88f0535549---Power`
 - **JFormFieldTimezone** | [Details](src/2c1cbfcd-55ea-40b9-9cd3-5ec02d8093cd) | [Settings](src/2c1cbfcd-55ea-40b9-9cd3-5ec02d8093cd/item.json) | JPK: `Joomla---2c1cbfcd_55ea_40b9_9cd3_5ec02d8093cd---Power`
 - **JFormFieldUrl** | [Details](src/59636bef-ad63-46a6-b3d0-1b5a57bb85fa) | [Settings](src/59636bef-ad63-46a6-b3d0-1b5a57bb85fa/item.json) | JPK: `Joomla---59636bef_ad63_46a6_b3d0_1b5a57bb85fa---Power`
 - **JFormFilterInt_Array** | [Details](src/28dee7b7-346d-4aec-8585-62752f502f1a) | [Settings](src/28dee7b7-346d-4aec-8585-62752f502f1a/item.json) | JPK: `Joomla---28dee7b7_346d_4aec_8585_62752f502f1a---Power`
 - **JHtmlAccess** | [Details](src/b649640e-d8d7-45be-bde9-3593b7a99a56) | [Settings](src/b649640e-d8d7-45be-bde9-3593b7a99a56/item.json) | JPK: `Joomla---b649640e_d8d7_45be_bde9_3593b7a99a56---Power`
 - **JHtmlActionsDropdown** | [Details](src/290f32aa-71d4-4ebc-9be5-5f8e305bc7e5) | [Settings](src/290f32aa-71d4-4ebc-9be5-5f8e305bc7e5/item.json) | JPK: `Joomla---290f32aa_71d4_4ebc_9be5_5f8e305bc7e5---Power`
 - **JHtmlAdminLanguage** | [Details](src/2f610b1b-799e-4318-8e05-efaa3aa3de0b) | [Settings](src/2f610b1b-799e-4318-8e05-efaa3aa3de0b/item.json) | JPK: `Joomla---2f610b1b_799e_4318_8e05_efaa3aa3de0b---Power`
 - **JHtmlBehavior** | [Details](src/172b70b8-8b24-4f07-8b1c-d7e7eb4618f0) | [Settings](src/172b70b8-8b24-4f07-8b1c-d7e7eb4618f0/item.json) | JPK: `Joomla---172b70b8_8b24_4f07_8b1c_d7e7eb4618f0---Power`
 - **JHtmlBootstrap** | [Details](src/524a8f19-1be0-44f7-8d8e-024f13919151) | [Settings](src/524a8f19-1be0-44f7-8d8e-024f13919151/item.json) | JPK: `Joomla---524a8f19_1be0_44f7_8d8e_024f13919151---Power`
 - **JHtmlCategory** | [Details](src/d1a074b7-ab65-46a1-8e55-f2cf8da4b8a2) | [Settings](src/d1a074b7-ab65-46a1-8e55-f2cf8da4b8a2/item.json) | JPK: `Joomla---d1a074b7_ab65_46a1_8e55_f2cf8da4b8a2---Power`
 - **JHtmlContent** | [Details](src/aa3544be-235f-43e5-850c-7bad5862b741) | [Settings](src/aa3544be-235f-43e5-850c-7bad5862b741/item.json) | JPK: `Joomla---aa3544be_235f_43e5_850c_7bad5862b741---Power`
 - **JHtmlContentlanguage** | [Details](src/305d5b6f-6ebf-40f1-b9f5-b44aa27c3925) | [Settings](src/305d5b6f-6ebf-40f1-b9f5-b44aa27c3925/item.json) | JPK: `Joomla---305d5b6f_6ebf_40f1_b9f5_b44aa27c3925---Power`
 - **JHtmlDate** | [Details](src/b1c4364a-7cf7-420b-b200-2997b0bfb2eb) | [Settings](src/b1c4364a-7cf7-420b-b200-2997b0bfb2eb/item.json) | JPK: `Joomla---b1c4364a_7cf7_420b_b200_2997b0bfb2eb---Power`
 - **JHtmlDebug** | [Details](src/966aae72-5e2e-4844-a34b-af7ad670208e) | [Settings](src/966aae72-5e2e-4844-a34b-af7ad670208e/item.json) | JPK: `Joomla---966aae72_5e2e_4844_a34b_af7ad670208e---Power`
 - **JHtmlDraggablelist** | [Details](src/c603424a-da38-4e7c-92fa-3e8ee35792c1) | [Settings](src/c603424a-da38-4e7c-92fa-3e8ee35792c1/item.json) | JPK: `Joomla---c603424a_da38_4e7c_92fa_3e8ee35792c1---Power`
 - **JHtmlDropdown** | [Details](src/6e5a6bbf-3ae1-4264-b3a6-db6c0b20c048) | [Settings](src/6e5a6bbf-3ae1-4264-b3a6-db6c0b20c048/item.json) | JPK: `Joomla---6e5a6bbf_3ae1_4264_b3a6_db6c0b20c048---Power`
 - **JHtmlEmail** | [Details](src/679a9d06-c5ff-4fd0-824c-9e26c3cb890f) | [Settings](src/679a9d06-c5ff-4fd0-824c-9e26c3cb890f/item.json) | JPK: `Joomla---679a9d06_c5ff_4fd0_824c_9e26c3cb890f---Power`
 - **JHtmlForm** | [Details](src/f07f4d81-4528-4221-ae1d-c28089ad38b5) | [Settings](src/f07f4d81-4528-4221-ae1d-c28089ad38b5/item.json) | JPK: `Joomla---f07f4d81_4528_4221_ae1d_c28089ad38b5---Power`
 - **JHtmlFormbehavior** | [Details](src/46d11f95-d0cb-48a0-bf44-eb5985f81395) | [Settings](src/46d11f95-d0cb-48a0-bf44-eb5985f81395/item.json) | JPK: `Joomla---46d11f95_d0cb_48a0_bf44_eb5985f81395---Power`
 - **JHtmlGrid** | [Details](src/ff31ae41-8106-4863-97b0-bb4bf6e3ebf4) | [Settings](src/ff31ae41-8106-4863-97b0-bb4bf6e3ebf4/item.json) | JPK: `Joomla---ff31ae41_8106_4863_97b0_bb4bf6e3ebf4---Power`
 - **JHtmlIcons** | [Details](src/7ef9f6f2-59e0-463d-bd3a-f31e2ee85451) | [Settings](src/7ef9f6f2-59e0-463d-bd3a-f31e2ee85451/item.json) | JPK: `Joomla---7ef9f6f2_59e0_463d_bd3a_f31e2ee85451---Power`
 - **JHtmlJGrid** | [Details](src/8c1ad286-fdbe-49b3-b4de-555b56425cb3) | [Settings](src/8c1ad286-fdbe-49b3-b4de-555b56425cb3/item.json) | JPK: `Joomla---8c1ad286_fdbe_49b3_b4de_555b56425cb3---Power`
 - **JHtmlJquery** | [Details](src/8ed6b791-f434-4407-9d55-498b7ec1ddbf) | [Settings](src/8ed6b791-f434-4407-9d55-498b7ec1ddbf/item.json) | JPK: `Joomla---8ed6b791_f434_4407_9d55_498b7ec1ddbf---Power`
 - **JHtmlLinks** | [Details](src/3474f0cb-43dc-4e0f-b05d-7ff934d443c7) | [Settings](src/3474f0cb-43dc-4e0f-b05d-7ff934d443c7/item.json) | JPK: `Joomla---3474f0cb_43dc_4e0f_b05d_7ff934d443c7---Power`
 - **JHtmlList** | [Details](src/87db9ce7-c772-407f-b154-f2b9a649fdc4) | [Settings](src/87db9ce7-c772-407f-b154-f2b9a649fdc4/item.json) | JPK: `Joomla---87db9ce7_c772_407f_b154_f2b9a649fdc4---Power`
 - **JHtmlMenu** | [Details](src/1f53a674-7173-472a-9fde-679b68266a3f) | [Settings](src/1f53a674-7173-472a-9fde-679b68266a3f/item.json) | JPK: `Joomla---1f53a674_7173_472a_9fde_679b68266a3f---Power`
 - **JHtmlNumber** | [Details](src/4cd834ca-7b73-4105-9058-28fd15a1605e) | [Settings](src/4cd834ca-7b73-4105-9058-28fd15a1605e/item.json) | JPK: `Joomla---4cd834ca_7b73_4105_9058_28fd15a1605e---Power`
 - **JHtmlSearchtools** | [Details](src/4081570d-1a8a-4c56-9454-347e060bc630) | [Settings](src/4081570d-1a8a-4c56-9454-347e060bc630/item.json) | JPK: `Joomla---4081570d_1a8a_4c56_9454_347e060bc630---Power`
 - **JHtmlSelect** | [Details](src/8097574b-722e-4b8c-b5b2-7bf8dff6535c) | [Settings](src/8097574b-722e-4b8c-b5b2-7bf8dff6535c/item.json) | JPK: `Joomla---8097574b_722e_4b8c_b5b2_7bf8dff6535c---Power`
 - **JHtmlSidebar** | [Details](src/ca5456e1-552c-45fb-bf4c-b751ba6e9fa1) | [Settings](src/ca5456e1-552c-45fb-bf4c-b751ba6e9fa1/item.json) | JPK: `Joomla---ca5456e1_552c_45fb_bf4c_b751ba6e9fa1---Power`
 - **JHtmlSortableList** | [Details](src/9d461911-59c1-4b2a-9abb-5bc83d268974) | [Settings](src/9d461911-59c1-4b2a-9abb-5bc83d268974/item.json) | JPK: `Joomla---9d461911_59c1_4b2a_9abb_5bc83d268974---Power`
 - **JHtmlString** | [Details](src/86a9e60d-ae43-4e29-8f33-78b9206e2145) | [Settings](src/86a9e60d-ae43-4e29-8f33-78b9206e2145/item.json) | JPK: `Joomla---86a9e60d_ae43_4e29_8f33_78b9206e2145---Power`
 - **JHtmlTag** | [Details](src/e10e9448-0b0c-4101-80c2-abe8f41c6a81) | [Settings](src/e10e9448-0b0c-4101-80c2-abe8f41c6a81/item.json) | JPK: `Joomla---e10e9448_0b0c_4101_80c2_abe8f41c6a81---Power`
 - **JHtmlTel** | [Details](src/80303734-98f9-4436-8e57-e73542abf4c1) | [Settings](src/80303734-98f9-4436-8e57-e73542abf4c1/item.json) | JPK: `Joomla---80303734_98f9_4436_8e57_e73542abf4c1---Power`
 - **JHtmlUser** | [Details](src/40a7483f-87c9-4272-ac72-236b0f773b02) | [Settings](src/40a7483f-87c9-4272-ac72-236b0f773b02/item.json) | JPK: `Joomla---40a7483f_87c9_4272_ac72_236b0f773b02---Power`
> remember to replace the `---` with `___` in the JPK to activate that Joomla! Power in your code

---
```
     ██╗ ██████╗  ██████╗ ███╗   ███╗██╗      █████╗
     ██║██╔═══██╗██╔═══██╗████╗ ████║██║     ██╔══██╗
     ██║██║   ██║██║   ██║██╔████╔██║██║     ███████║
██   ██║██║   ██║██║   ██║██║╚██╔╝██║██║     ██╔══██║
╚█████╔╝╚██████╔╝╚██████╔╝██║ ╚═╝ ██║███████╗██║  ██║
 ╚════╝  ╚═════╝  ╚═════╝ ╚═╝     ╚═╝╚══════╝╚═╝  ╚═╝
 ██████╗ ██████╗ ███╗   ███╗██████╗  ██████╗ ███╗   ██╗███████╗███╗   ██╗████████╗
██╔════╝██╔═══██╗████╗ ████║██╔══██╗██╔═══██╗████╗  ██║██╔════╝████╗  ██║╚══██╔══╝
██║     ██║   ██║██╔████╔██║██████╔╝██║   ██║██╔██╗ ██║█████╗  ██╔██╗ ██║   ██║
██║     ██║   ██║██║╚██╔╝██║██╔═══╝ ██║   ██║██║╚██╗██║██╔══╝  ██║╚██╗██║   ██║
╚██████╗╚██████╔╝██║ ╚═╝ ██║██║     ╚██████╔╝██║ ╚████║███████╗██║ ╚████║   ██║
 ╚═════╝ ╚═════╝ ╚═╝     ╚═╝╚═╝      ╚═════╝ ╚═╝  ╚═══╝╚══════╝╚═╝  ╚═══╝   ╚═╝
██████╗ ██╗   ██╗██╗██╗     ██████╗ ███████╗██████╗
██╔══██╗██║   ██║██║██║     ██╔══██╗██╔════╝██╔══██╗
██████╔╝██║   ██║██║██║     ██║  ██║█████╗  ██████╔╝
██╔══██╗██║   ██║██║██║     ██║  ██║██╔══╝  ██╔══██╗
██████╔╝╚██████╔╝██║███████╗██████╔╝███████╗██║  ██║
╚═════╝  ╚═════╝ ╚═╝╚══════╝╚═════╝ ╚══════╝╚═╝  ╚═╝
```
> Build with [Joomla Component Builder](https://git.vdm.dev/joomla/Component-Builder)

