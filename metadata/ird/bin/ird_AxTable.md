   IRD_CustHoldTable��g5    �  Ird_AssetStructure��g5�  +  Ird_CustSalesOrderTable��g5  4  IrdCustInvTable��g5K  �  SpeakerStaging��g5�	    Ird_BookingOrigin��g5    IrdSalesOrders��g5  �  TmpSpeakerTable��g5  �  ird_speakerspecialization��g5   �  IrdPurchTable��g5�  �  ird_speaker��g5Z  �  IrdPurchTypeTable��g5  �   Ird_CustBusinessEventLog��g5�  �  awm_pricelists��g5�!  W  � �
 3public class IRD_CustHoldTable extends common
{
}   �   �CustAccount��CustBlocked�
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��   �CustAccount��CustBlocked�
AutoBrowse�   �	CustAccountCustAccount��CustVendorBlocked	CustBlockedCustBlocked��
ProcStatus
ProcStatus�   �    �CustAccount�	
AccountIdx� @ird_labels:CustHoldInterfaceTab   � 
clear�  � �!IRD_CustHoldTable$
AccountIdx9  �0 3CustAccount�� �A 4public class Ird_AssetStructure extends common
{
}   �
AutoReport��   �Ird_structureCode��Ird_strucDesc�
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse��   �Ird_structureCode��Ird_strucDesc�
FormFields�   �    SysRowVersionNumberSysRowVersionNumber ��	ExtCodeCodeStructure CodeIrd_structureCode��	CatalogDescriptionDescriptionIrd_strucDesc�   �    �Ird_structureCode�	StructureCode�IRD Asset Structure!Ird_AssetStructure9  �3Ird_structureCode4Ird_strucDesc�� �A 9public class Ird_CustSalesOrderTable extends common
{
}   �   �CustAccountNum��SalesId��ItemId�
AutoReport��   �CustAccountNum��SalesId��ItemId�
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse��   �CustAccountNum��SalesId��ItemId�FormDisplay�   �    SysRowVersionNumberSysRowVersionNumber ��	
AccountNum	@SYS16716CustAccountNum��	SalesId$@RevenueRecognition:SalesOrderNumberSalesId��	ItemId"@HierarchicalGridCommon:ItemNumberItemId�   �    �CustAccountNum�	CustAccountNum�@IrdCustSOTable   � 	
find   � _custaccountnum 
AccountNum�� 
_forupdate boolean��  Ird_CustSalesOrderTable� �� 	
exist   � _custaccountnum 
AccountNum��  boolean� �!Ird_CustSalesOrderTable9  ��� �A 1public class IrdCustInvTable extends common
{
}   �   �CustAccountNum��SalesId��ItemId�
AutoReport��   �CustAccountNum��SalesId��ItemId�
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse��   �CustAccountNum��SalesId��ItemId�FormDisplay�   �    SysRowVersionNumberSysRowVersionNumber ��	
AccountNumAccount NumberCustAccountNum��	SalesIdSales OrderSalesId��	ItemIdItem NumberItemId�   �    �CustAccountNum�	CustAccountNum�IR Cust Sales Orders   � 	
find   � _custaccountnum 
AccountNum�� 
_forupdate boolean��  IrdCustInvTable� �!IrdCustInvTable9  ��� �"@DMF:StagingDeveloperDocumentation   � 
AutoReport�� 
AutoLookup��  AutoIdentification�� AutoSummary�� 
AutoBrowse��   �DefinitionGroup��
IsSelected��TransferStatus��ExecutionId� @DMF:StagingExtensionGroupExtensionList�
   �  	DMFDefinitionGroupName  DefinitionGroup<   ��  	DMFExecutionId  ExecutionIdZ   ��NoYes	DMFIsSelected 
IsSelected��DMFTransferStatus TransferStatus��SpeakerStatus @ird_labels:Ird01SpeakerStatus��	Name @ird_labels:Ird04	FirstName��	LastName @ird_labels:Ird05LastName��	Email @ird_labels:Ird06Email��	Name @ird_labels:Ird07SpeakerSpecialization��	EmplNameSpeaker Full NameSpeakerFullName�
SpeakersMI   �    �DefinitionGroup��ExecutionId��Email� 	
StagingIdx�@ird_labels:Ird14!SpeakerStaging$
StagingIdx%   �    �EmailEmailEmail�(@DMF:StagingToDataEntityRelationshipRole 	
DataEntitySpeaker    �&
StagingIdx(  0 3	FirstName4SpeakerStatus�� �A 3public class Ird_BookingOrigin extends common
{
}   �
AutoReport��   �IrdBookingOrigin�
AutoLookup�� AutoIdentification��AutoSummary��   �IrdBookingOrigin�
AutoBrowse�   �Booking OriginIrdBookingOrigin�!Ird_BookingOrigin9  ��� �>  A SalesOrderIdx	 
 0public class IrdSalesOrders extends common
{
}@LTM:SalesTable   �   �SalesOrderId��SalesOrderDate��SalesOrderAccount�
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse�
   �	SalesId@TRX43 SalesOrderId��SalesLineDlvDate@GLS6532SalesOrderDate��    SysRowVersionNumberSysRowVersionNumber ��Amount	@MCR10906SalesOrderTotal��	CustAccount#@AccountsReceivable:CustomerAccount SalesOrderAccount��	CustAccount#@AccountsReceivable:CustomerAccountInvoiceAccount��  @TRX1830	SalesGUID��	OrderType	OrderType��	SalesTakerPersonnelNumber
@SYS310060
SalesRepId��	Description@SCM:DescriptionDescription�   �    �SalesOrderId�	SalesOrderIdx�:@GlobalUnifiedPricing:GUPPricingAttributeSource_SalesTable   � 
CustAccountName�  AccountName� �� 

getsalesid� 
  � �;
SalesOrder!IrdSalesOrders$SalesOrderIdx9  �0 3SalesOrderId4Description�� �>  1public class TmpSpeakerTable extends common
{
}   �   �SpeakerStatus��	FirstName��LastName��Email��SpeakerSpecialization�
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse�   �SpeakerStatus@ird_labels:Ird01SpeakerStatus��	Name@ird_labels:Ird04	FirstName��	LastName@ird_labels:Ird05LastName��	Email@ird_labels:Ird06Email��	Name@ird_labels:Ird07SpeakerSpecialization�@ird_labels:Ird18!TmpSpeakerTable9  �1 �� �A 	 
 ;public class ird_speakerspecialization extends common
{
}   �   �specialization�
AutoReport��   �specialization�
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse��   �specialization�FormDS�   �    SysRowVersionNumberSysRowVersionNumber ��	Name@ird_labels:ird08specialization�@ird_labels:Ird08!ird_speakerspecialization9  �0 3specialization�� �>  /public class IrdPurchTable extends common
{
}@ird_labels:IrdPurchTable   �   �
PurchReqID��Description��PurchReqRequisitionStatus��PurchReqType��ReqDate�
AutoReport��   �
PurchReqID��PurchReqType�
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse�   �	SimplePurchReqId@ird_labels:PurchReqID
PurchReqID��	Description@AssetLeasing:DescriptionDescription��PurchReqRequisitionStatusPurchReqRequisitionStatus��PurchReqTypePurchReqType��PurchReqRequiredDate@ird_labels:ReqDateReqDate�   �   �
PurchReqID�	IrdPurcReqIdx�@ird_labels:IrdPurchTable!IrdPurchTable9  �0
 3
PurchReqID4Description�� �>   	 
 �public class ird_speaker extends common
{
    /// <summary>
    /// find method
    /// </summary>
    /// <param> for update to be used as boolean
    /// _email to be used as email parma</param>
    
}@ird_labels:Ird13   �   �SpeakerSpecialization��Email��LastName��	FirstName��SpeakerStatus�
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse��   �SpeakerStatus��	FirstName��LastName��IrdModeOfCommunication��Email��SpeakerSpecialization��AllocatedHours��ActualHours�@ird_labels:IRD12FormDS�   �SpeakerStatus@ird_labels:Ird01SpeakerStatus��	Name@ird_labels:Ird04	FirstName��	LastName@ird_labels:Ird05LastName��	Email@ird_labels:Ird06Email��	Name@ird_labels:Ird07SpeakerSpecialization��FullQtyAllocated HoursAllocatedHours��Actual HoursActualHours��IrdModeOfCommunication
Comms ModeIrdModeOfCommunication�
SpeakersMI   �    �Email�	
SpeakerIdx�@ird_labels:IRD12   � 	
find   � _email Email�� false
_forupdate boolean��  ird_speaker� �� 	
exist   � _email Email��  boolean� �� 
Fullname�  Name� �� 
	initValue�  � �!ird_speaker$
SpeakerIdx%   �    �SpeakerSpecializationSpeakerSpecializationspecialization�SpeakerToSpecializationird_speakerspecialization  �9  �0 3	FirstName4SpeakerStatus�� �>  3public class IrdPurchTypeTable extends common
{
}   �
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse�   �Purcahse TypeIrdPurchType�Purchase Type!IrdPurchTypeTable9  �0 �� �A :public class Ird_CustBusinessEventLog extends common
{
}   �
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse�   �    SysRowVersionNumberSysRowVersionNumber ��	BusinessEventsIdEvent IdEventId��	BusinessEventsCDSContextEvent Context	MessageId�   �    �EventId�	EventId�Business Event Log!Ird_CustBusinessEventLog9  ��� � 	 
 0public class awm_pricelists extends common
{
}   �   �PriceListName��	StartDate��EndDate��Currency�
AutoReport��   �PriceListName�
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse��   �PriceListName��	StartDate��EndDate��Currency�FormDisplay�   �	NamePrice List Name PriceListName��dateDDMMYYYY
Start Date	StartDate��dateDDMMYYYYEnd DateEndDate��	CurrencyCodeCurrencyCurrency�Price Lists  !awm_pricelists%   �    �CurrencyCurrencyCurrencyCode�CurrencyCurrency �9  ��