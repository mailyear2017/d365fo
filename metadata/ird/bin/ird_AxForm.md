
   IrdPurchReqSLD��g5    �  IrdFornHeader��g5�  �  SpeakersForm��g5L  �  IrdCustSOForm��g5�  �  IrdSalesForm��g5�  �  IrdPurchRequestTypeForm��g5�  _  AWMPriceList��g5  �  Specializations_form��g5�  �  Ird_AssetStructure��g5�   ,  IrdBookingOrigin��g5�#  p  � �    � 	   � 
DataAreaId�� Description�� 	Partition�� 
PurchReqID�� PurchReqRequisitionStatus�� PurchReqType�� RecId�� ReqDate�� TableId�     � 
create   � false_append boolean��  � �� 
	initValue�  � �IrdPurchTableIrdPurchTable�� 
 �@ird_labels:IrdPurchTable   � IrdPurchTable)ApplicationPane�� 
 �   � �    � targetControlName LeftGridControl_PurchReq�� placeholderText �� defaultColumnName IrdPurchTable_PurchReqID�QuickFilterControl�QuickFilter_PurchReq& ��  � �   �   �  �
PurchReqIDIrdPurchTable' �6 �GIrdPurchTable_PurchReqID��  �DescriptionIrdPurchTable' �6 �GIrdPurchTable_Description�2  3LeftGridControl_PurchReq;  = K �* , <NavigationGridF �� 
 �     �  �
PurchReqIDIrdPurchTable' �6 �GIrdPurchTable_PurchReqID1��  �DescriptionIrdPurchTable' �6 �GIrdPurchTable_Description1�* <HeaderDetails@FieldsFieldGroupsA1.1S �� 
 �   � 
 �@ird_labels:IrdPurchTable     �  �PurchReqTypeIrdPurchTable% �5 �@IrdPurchTable_PurchReqType��  �ReqDateIrdPurchTable, �; �KIrdPurchTable_ReqDate��  �PurchReqRequisitionStatusIrdPurchTable% �5 �@'IrdPurchTable_PurchReqRequisitionStatus�0FormTabPageControl_PurchReq5FieldsFieldGroups61.1�0
DetailsTab< �IrdPurchTable0SimpleListDetails11.3: �
   � 
classDeclaration� ��IrdPurchReqSLD�� � � 
 �   � 
 �     � 
 �   �  �displayIsValid% �5 �@FormComboBoxControl1�<FormGroupControl2�, <FormGroupControl1@FieldsFieldGroupsA1.1F S ��  
 �   �  �" �0ok��  �" �0Cancel;  ��  �" �.   � 
clicked�  � �0validate�5FormButtonGroupControl1@ L �0Dialog11.2: �   " 
    FormObservable�valid boolean�
   � 
classDeclaration� ��� 
displayIsValid�  boolean� �IrdFornHeader�� �    �    � ActualHours�� AllocatedHours   � 
modified�  � ��� 	CreatedBy�� CreatedDateTime�� 
DataAreaId�� Email�� 	FirstName�� IrdModeOfCommunication   � 
modified�  � ��� LastName�� 	Partition�� RecId�� SpeakerSpecialization�� SpeakerStatus�� TableId�   � 
active�   � �� 
init�  � �� 
executeQuery�  � �� 
selectionChanged�  � �ird_speakerird_speaker�� 
 �@ird_labels:IRD12   � )FormActionPane��  
 �   � �    � targetControlName Grid�� placeholderText �� defaultColumnName Grid_FirstName�QuickFilterControl�QuickFilter�* <CustomFilterGroup@CustomAndQuickFiltersA1.1F P S ��  � � �	   �  �SpeakerStatusird_speaker% �5 �@Grid_SpeakerStatus��  �	FirstNameird_speaker' �6 �GGrid_FirstName��  �LastNameird_speaker' �6 �GGrid_LastName��  �IrdModeOfCommunicationird_speaker% �5 �@Grid_IrdModeOfCommunication��  �Emailird_speaker' �6 �G
Grid_Email��  �SpeakerSpecializationird_speaker' �6 �GGrid_SpeakerSpecialization��   �AllocatedHoursird_speaker) �8 �F   � 
modified�  boolean� �GGrid_AllocatedHours��  	 �ActualHoursird_speaker+ �; �LGrid_ActualHours��  �Fullnameird_speaker' �6 �GFullName_Display�ird_speaker3Grid= �ird_speaker0
SimpleList11.1: <ird_speaker�
   � 
classDeclaration� ��SpeakersForm�� �    �    � CustAccountNum�� 
DataAreaId�� ItemId�� 	Partition�� RecId�� SalesId�� SysRowVersionNumber�� TableId�   � 
executeQuery�  � �Ird_CustSalesOrderTableIrd_CustSalesOrderTable�� 
 �@ird_labels:IrCustSOForm   � )FormActionPaneControl1��  
 �   � �    � targetControlName FormGridControl1�� placeholderText �� defaultColumnName FormDisplay_CustAccountNum�QuickFilterControl�QuickFilterControl1�* <FormGroupControl1@CustomAndQuickFiltersA1.1F P S ��  � � �   � 
 �   �  �CustAccountNumIrd_CustSalesOrderTable' �6 �GFormDisplay_CustAccountNum��  �SalesIdIrd_CustSalesOrderTable' �6 �GFormDisplay_SalesId��  �ItemIdIrd_CustSalesOrderTable' �6 �GFormDisplay_ItemId�FormDisplayIrd_CustSalesOrderTable<FormDisplay�Ird_CustSalesOrderTable3FormGridControl1= �Ird_CustSalesOrderTable0
SimpleList11.1: �
   � 
classDeclaration� ��� 
init�  � �IrdCustSOForm�� �    �    � 	CreatedBy�� CreatedDateTime�� 
DataAreaId�� Description�� InvoiceAccount�� 	OrderType�� 	Partition�� RecId�� 	SalesGUID�� SalesOrderAccount�� SalesOrderDate�� SalesOrderId�� SalesOrderTotal�� 
SalesRepId�� SysRowVersionNumber�� TableId�IrdSalesOrdersIrdSalesOrders�� 
 �   � )FormActionPaneControl1��  
 �   � �    � targetControlName �� placeholderText �� defaultColumnName �QuickFilterControl�QuickFilterControl1�* <FormGroupControl1@CustomAndQuickFiltersA1.1F P S ��  � � �   � 
 �   �  �SalesOrderAccountIrdSalesOrders' �0Order Account6 �G IrdSalesOrders_SalesOrderAccount��  �InvoiceAccountIrdSalesOrders' �0Invoice Account6 �GIrdSalesOrders_InvoiceAccount��  �
SalesRepIdIrdSalesOrders' �6 �GIrdSalesOrders_SalesRepId�<SalesAccGrp�� 
 �   �  �SalesOrderIdIrdSalesOrders' �6 �GIrdSalesOrders_SalesOrderId��  �DescriptionIrdSalesOrders' �6 �GIrdSalesOrders_Description��  �	OrderTypeIrdSalesOrders% �5 �@IrdSalesOrders_OrderType��  �SalesOrderDateIrdSalesOrders, �; �KIrdSalesOrders_SalesOrderDate��  �
getsalesidIrdSalesOrders& �5 �DIrdSalesOrders_SalesGUID�<
SalesIDGrp�� 
 �   � 	 �SalesOrderTotalIrdSalesOrders+ �; �LIrdSalesOrders_SalesOrderTotal��  �CustAccountNameIrdSalesOrders' �0Account Name6 �GDisplayMethodStrCtrlVAccount Name�<SalesTotalsGrp�3	SalesGrid= �0
SimpleList11.1: �
   � 
classDeclaration� ��IrdSalesForm�� �    �    � 
DataAreaId�� IrdPurchType�� 	Partition�� RecId�� TableId�IrdPurchTypeTableIrdPurchTypeTable�� 
 �   � )PurchTypeActionPane��  
 �   � �    � targetControlName MainGrid�� placeholderText �� defaultColumnName IrdPurchTypeTable_IrdPurchType�QuickFilterControl�PTQuickFilter�* <PurchTypeFilterGroup@CustomAndQuickFiltersA1.1F P S ��  � � �   �  �IrdPurchTypeIrdPurchTypeTable' �6 �GIrdPurchTypeTable_IrdPurchType�IrdPurchTypeTable3MainGrid= �0
SimpleList11.1: �
   � 
classDeclaration� ��IrdPurchRequestTypeForm�� �    �    � 	CreatedBy�� CreatedDateTime�� Currency�� 
DataAreaId�� EndDate�� 
ModifiedBy�� ModifiedDateTime�� 	Partition�� PriceListName�� RecId�� 	StartDate�� TableId�awm_pricelistsawm_pricelists�� 
 �   � Price Lists)PricelistActionPane��  
 �   � �    � targetControlName PriceListGridControl1�� placeholderText �� defaultColumnName FormDisplay_PriceListName�QuickFilterControl�PriceListQF�awm_pricelists* <CustomFiltergroup@CustomAndQuickFiltersA1.1F P S ��  � � �   � 
 �   �  �PriceListNameawm_pricelists' �6 �GPriceListNameControl��  �	StartDateawm_pricelists, �; �KStartDateControl��  �EndDateawm_pricelists, �; �KEndDateControl��  �Currencyawm_pricelists' �6 �GCurrencyControl�FormDisplayawm_pricelists<FormDisplay�3PriceListGridControl1= �0
SimpleList11.1: �
   � 
classDeclaration� ��AWMPriceList�� �    �    � 	CreatedBy�� CreatedDateTime�� 
DataAreaId�� 	Partition�� RecId�� specialization�� SysRowVersionNumber�� TableId�   � 
editSpecialization   � set boolean�� 
irdspectab ird_speakerspecialization�� _newval Name��  Name� �� 
maskspec�  Name� �ird_speakerspecializationird_speakerspecialization�� 
 �@ird_labels:Ird08   � )
ActionPane��  
 �   � �    � targetControlName ListPageGrid�� placeholderText �� defaultColumnName specialization�QuickFilterControl�
QFSpecName�ird_speakerspecialization* <Filter@CustomAndQuickFiltersA1.1F P S ��  � � �   �  �specializationird_speakerspecialization' �0@ird_labels:Ird086 �Gspecialization��  �maskspecird_speakerspecialization' �0	Edit Demo6 �GEditDemoStr01�ird_speakerspecialization3ListPageGrid= �ird_speakerspecialization0
SimpleList11.1: <ird_speakerspecialization� 
   � 
classDeclaration� ��Specializations_form�� �    �    � 
DataAreaId�� Ird_strucDesc�� Ird_structureCode�� 	Partition�� RecId�� SysRowVersionNumber�� TableId�Ird_AssetStructureIrd_AssetStructure�� 
 �Asset Structure   � )Ird_AssetStrucActionPane��  
 �   � �    � targetControlName Ird_AssetStrucGrid�� placeholderText �� defaultColumnName $Ird_AssetStrucGrid_Ird_structureCode�QuickFilterControl�Ird_QuickFilter�* <Id_AssetStrucFormGroup@CustomAndQuickFiltersA1.1F P S ��  � � �   �  �Ird_structureCodeIrd_AssetStructure' �6 �G$Ird_AssetStrucGrid_Ird_structureCode��  �Ird_strucDescIrd_AssetStructure' �6 �G Ird_AssetStrucGrid_Ird_strucDesc�
FormFieldsIrd_AssetStructure3Ird_AssetStrucGrid= �0
SimpleList11.1: �
   � 
classDeclaration� ��Ird_AssetStructure�� �    �    � 
DataAreaId�� IrdBookingOrigin�� 	Partition�� RecId�� TableId�Ird_BookingOriginIrd_BookingOrigin�� 
 �   � )IrdBookingOriginAP��  
 �   � �    � targetControlName IrdBookingOrigin�� placeholderText �� defaultColumnName "Ird_BookingOrigin_IrdBookingOrigin�QuickFilterControl�IrdQuickFilter�* <IrdFilterGrp@CustomAndQuickFiltersA1.1F P S ��  � � �   �  �IrdBookingOriginIrd_BookingOrigin' �6 �G"Ird_BookingOrigin_IrdBookingOrigin�Ird_BookingOrigin3IrdBookingOrigin= �0
SimpleList11.1: �
   � 
classDeclaration� ��IrdBookingOrigin�