/   IrdClassDemoWithStr��g5       tableinsert01��g5   s   IrdCallQueryClass��g5�   {   	SpeakerDP��g5m  V  IrdExportDataToFile��g5�     IrdWoStatusUpdateController��g5B  �  TestSpeakerRDP��g5�  u   IrdGetDimValues��g5d  w   IrdCopyDataFromField��g5�  �   Parent_DatatoTables��g5\  �   populateIrdCustSOTable��g5  �   IrdSalesConfBusEventContract��g5�  j  IrdDeleteHourJournals��g5�  �   IrdCustDataResponse��g5}    Irdcoc01_Extension��g5~  T  IrdCreateHourJournal��g5�  �   IrdCustDataService��g5�  �   IrdTableEventHandlerClass��g5X  w  Ircoc01��g5�  �   IrdWoStatusUpdateContract��g5x  �  Ird_CustOnHoldController��g5  �  IrdLoadSimplePurchReqNumSeq��g5�  �   IrdCrossCompDemo��g5I  y   IrdFormClassDemo01��g5�  �   SpeakerDataContract��g5n  �  DocuRef_C_Extension��g5b   3  $IrdSalesConfirmJournalPost_Extension��g5�!    IrdPurchReqIDNumSeq��g5�"    IrdFindLatLongForLocation��g5�$  �   IrdCustDataRequest��g5�%  @  IrdEntAssetLifeCycleUpdate_WO��g5�&  �  Ird_GetEntitySQL��g5�)  y   #CustTable_CustGroupModIRD_Extension��g5*  �  Students��g5�+  �   Ird_CustHoldService��g5o,  �   IrdCrossCompDemo02��g5^-  }   IrdHCMGoal_Extension��g5�-  �   Demo_ArgClass��g5�.  q   CustTable_Ird_Extension��g5E/  �   Ird_CustOnHoldContract��g5@0  �  SpeakerForm_COC_Extension��g5'3  	  IrdSalesConfBusinessEvent��g504  �  IrdWoStatusUpdateService��g5�7  �   IrdQueryclassdemo��g5�8  �   Ird_speakerTab_findMethodCheck��g5Z9  �   PopulateDataToTables��g5':  �  #Ird_EntAssetObjectTable_F_Extension��g5�;  J  � ! .internal final class IrdClassDemoWithStr
{
}   � 	
main   � _args Args��  � �IrdClassDemoWithStr�� ! (internal final class tableinsert01
{
}   � 	
main   � _args Args��  � �tableinsert01�� ! ,internal final class IrdCallQueryClass
{
}   � 	
main   � _args Args��  � �IrdCallQueryClass�� !     SrsReportQueryAttribute    'SpeakerQuery'�� SRSReportparameterAttribute        SpeakerDataContract� � � classStr���[SrsReportQueryAttribute('SpeakerQuery')
,SRSReportparameterAttribute(classStr(SpeakerDataContract))
    ]
public class SpeakerDP extends SRSReportDataProviderBase
{
    TmpSpeakerTable     tmpSpeakerTable;

}SRSReportDataProviderBase   " tmpSpeakerTable TmpSpeakerTable�   �     SrsReportDataSetAttribute    'tmpSpeakerTable'��
getTmpSpeakerTable�  TmpSpeakerTable� �� 
processReport�  � �	SpeakerDP�� ! .internal final class IrdExportDataToFile
{
}   � 	
main   � _args Args��  � �IrdExportDataToFile�� ! `internal final class IrdWoStatusUpdateController extends SysOperationServiceController
{
  
}SysOperationServiceController   � 
new�  � �� 
defaultcaption�  ClassDescription� �� 	
	construct   � &SysOperationExecutionMode::Synchronous_executionmode SysOperationExecutionMode��  IrdWOStatusUpdateController� �� 	
main   � _args Args��  � �IrdWoStatusUpdateController�� ! )internal final class TestSpeakerRDP
{
}   � 	
main   � _args Args��  � �TestSpeakerRDP�� ! *internal final class IrdGetDimValues
{
}   � 	
main   � _args Args��  � �IrdGetDimValues�� ! /internal final class IrdCopyDataFromField
{
}   � 	
main   � _args Args��  � �IrdCopyDataFromField�� ! Jclass Parent_DatatoTables
{

    Args    _arg=new Args();
    
   
}   " _arg Args�   � 	
main   � _arg Args��  � �Parent_DatatoTables�� ! 1internal final class populateIrdCustSOTable
{
}   � 	
main   � _args Args��  � �populateIrdCustSOTable�� !     DataContract��[DataContract]
public final class IrdSalesConfBusEventContract extends BusinessEventsContract
{
    private SalesId salesId;
    private DataAreaId  dataAreaId;
    private String50    salesStatus;


}BusinessEventsContract   " salesId SalesId	  �" 
dataAreaId 
DataAreaId	  �" salesStatus String50	  �   �     
DataMember    'SalesOrderId'�� !BusinessEventsDataMemberAttribute    "Sales Order Id"��
parmSalesId   � salesId_salesid SalesId��  SalesId� ��     
DataMember    'LegalEntityId'�� !BusinessEventsDataMemberAttribute    "Legal Entity"��
parmDataAreaId   � 
dataAreaId_dataAreaId 
DataAreaId��  
DataAreaId� ��     
DataMember    'SalesStatus'�� !BusinessEventsDataMemberAttribute    "Sales Status"��
parmSalesStatus   � salesStatus_salesStatus String50��  String50� �� 

initialize   � _salesTable 
SalesTable��  � �� 	
newFromSalesTable   � _salesTable 
SalesTable��  IrdSalesConfBusEventContract� �IrdSalesConfBusEventContract�� ! 0internal final class IrdDeleteHourJournals
{
}   � 	
main   � _args Args��  � �IrdDeleteHourJournals�� !     DataContractAttribute��[DataContractAttribute]
public final class IrdCustDataResponse
{
    private AccountName accountname;
    private boolean success;
    private str errormessage;
    private Amount  openbal;

}   " accountname AccountName	  �" success boolean	  �" errormessage  	  �" openbal Amount	  �   �     
DataMember�
parmAccountName   � accountname_value AccountName��  AccountName� ��     
DataMember�
parmSuccess   � success_value boolean��  boolean� ��     
DataMember�
parmErrorMessage   � errormessage_value  ��   � ��     
DataMember�
parmCustOpenBal   � openbal_value Amount��  Amount� �IrdCustDataResponse�� !     ExtensionOf        Ircoc01� � � classStr���/// <summary>
/// this class demonstrates the chain of command
/// </summary>
[ExtensionOf(classStr(Ircoc01))]
final class Irdcoc01_Extension
{
}   � 
dosomething   � c  ��   � �� 	
main   � args Args��  � �Irdcoc01_Extension�� ! /internal final class IrdCreateHourJournal
{
}   � 	
main   � _args Args��  � �� 	
GetJournalName�  JournalNameId� �� 
GetNextVoucher�   � �� 
GetJourHdrId�   � �IrdCreateHourJournal�� ! &public class IrdCustDataService
{ 
}   � 
Create   � _request IrdCustDataRequest��  IrdCustDataResponse� �IrdCustDataService�� ! z/// <summary>
/// event handler class wrapper
/// </summary>
internal final class IrdTableEventHandlerClass
{
    
}   �     DataEventHandler        awm_pricelists� � � tableStr�     	Inserting�	 DataEventType��	
awm_pricelists_onInserting   � sender Common�� e DataEventArgs��  � �IrdTableEventHandlerClass�� ! d/// <summary>
/// This is main class for the COC demo
/// </summary>
public class Ircoc01
{

}   � 
dosomething   � arg  ��   � �Ircoc01�� !     DataContractAttribute��[DataContractAttribute]
internal final class IrdWoStatusUpdateContract
{
    EntAssetWorkOrderLifecycleStateRecId fromstatus, tostatus;
    EntAssetWorkOrderID fromworkorderid, toworkorderid;
    
}   " 
fromstatus $EntAssetWorkOrderLifecycleStateRecId�" tostatus $EntAssetWorkOrderLifecycleStateRecId�" fromworkorderid EntAssetWorkOrderID�" toworkorderid EntAssetWorkOrderID�   �     
DataMember� SysOperationLabel    "From Work Order"�� SysOperationDisplayOrder    "1"��
ParmFromWorkOrderId   � fromworkorderid_fromworkorderid EntAssetWorkOrderID��  EntAssetWorkOrderID� ��     
DataMember� SysOperationLabel    "To Work Order"�� SysOperationDisplayOrder    "2"��
ParmToWorkOrderId   � toworkorderid_toworkorderid EntAssetWorkOrderID��  EntAssetWorkOrderID� ��     
DataMember� SysOperationLabel    "From LifeCyle State"�� SysOperationDisplayOrder    "3"��
ParmFromStatus   � 
fromstatus_fromstatus $EntAssetWorkOrderLifecycleStateRecId��  $EntAssetWorkOrderLifecycleStateRecId� ��     
DataMember� SysOperationLabel    "To LifeCycleState"�� SysOperationDisplayOrder    "4"��
ParmToStatus   � tostatus	_tostatus $EntAssetWorkOrderLifecycleStateRecId��  $EntAssetWorkOrderLifecycleStateRecId� �IrdWoStatusUpdateContract�� ! Yinternal final class Ird_CustOnHoldController extends SysOperationServiceController
{
}SysOperationServiceController   � 
new�  � �� 
DefaultCaption�  ClassDescription� �� 	
	Construct   � &SysOperationExecutionMode::Synchronous_executionmode SysOperationExecutionMode��  Ird_CustOnHoldController� �� 	
main   � _args Args��  � �Ird_CustOnHoldController�� ! 6internal final class IrdLoadSimplePurchReqNumSeq
{
}   � 	
main   � _args Args��  � �IrdLoadSimplePurchReqNumSeq�� ! +internal final class IrdCrossCompDemo
{
}   � 	
main   � _args Args��  � �IrdCrossCompDemo�� ! \/// <summary>
///demo class 
/// </summary>
internal final class IrdFormClassDemo01
{
}   � 	
main   � _args Args��  � �IrdFormClassDemo01�� !     DataContractAttribute��[DataContractAttribute]
//internal final class SpeakerDataContract
public class SpeakerDataContract implements SysOperationValidatable
{
    SpeakerStatus   speakerStatus;

}   SysOperationValidatable   " speakerStatus SpeakerStatus�   �     DataMemberAttribute    "Status"��
parmSpeakerStatus   � speakerStatus_speakerStatus SpeakerStatus��  SpeakerStatus� �� 
validate�  boolean� �SpeakerDataContract�� !     ExtensionOf        DocuRef� � � tableStr���[ExtensionOf(tableStr(DocuRef))]
/// <summary>
/// 
/// Extending initvalue method to default the document type 
/// </summary>

internal final class DocuRef_C_Extension
{
}   � 
	initValue�  � �DocuRef_C_Extension�� !     ExtensionOf        SalesConfirmJournalPost� � � classStr��q[ExtensionOf(classStr(SalesConfirmJournalPost))]
internal final class IrdSalesConfirmJournalPost_Extension
{
}   � 
endPost�  � �$IrdSalesConfirmJournalPost_Extension�� ! �/// <summary>
/// class for registering the application module
/// </summary>
internal final class IrdPurchReqIDNumSeq extends NumberSeqApplicationModule
{
    ///

}NumberSeqApplicationModule   � 
numberSeqModule�  NumberSeqModule� ��     SubscribesTo        NumberSeqGlobal� � � classStr�     NumberSeqGlobal� buildModulesMapDelegate� � delegateStr��	
buildModulesMapSubscriber   � numberSeqModulesMap Map��  � �� 

loadModule�  � �IrdPurchReqIDNumSeq�� ! 4internal final class IrdFindLatLongForLocation
{
}   � 	
main   � _args Args��  � �� 

GetAddress   � _logisticslocation RecId��   � �IrdFindLatLongForLocation�� !     DataContractAttribute�k[DataContractAttribute]
public final class IrdCustDataRequest
{
    private AccountNum  accountnum;

}   " 
accountnum 
AccountNum	  �   �     
DataMember�
parmCustAccountNum   � 
accountnum_value 
AccountNum��  
AccountNum� �IrdCustDataRequest�� ! �public final class IrdEntAssetLifeCycleUpdate_WO extends EntAssetLifecycleStateUpdate_WorkOrderTable
{
   //EntAssetLifecycleStateUpdate_WorkOrderTable workorderstateupdate = EntAssetLifecycleStateUpdate::construct(tableStr(EntAssetWorkOrderTable));
    EntAssetWorkOrderLifecycleState workOrderLifecycleStateloc;
    
   

}+EntAssetLifecycleStateUpdate_WorkOrderTable   " workOrderLifecycleStateloc EntAssetWorkOrderLifecycleState�   � 
updateLifecycleState�  � �� 
	updateLog   � _recid RecId��  � �� 
WOStatusupdate   � _wotable EntAssetWorkOrderTable��  � �� 	
	construct�  IrdEntAssetLifeCycleUpdate_WO� �IrdEntAssetLifeCycleUpdate_WO�� ! +internal final class Ird_GetEntitySQL
{
}   � 	
main   � _args Args��  � �Ird_GetEntitySQL�� !     ExtensionOf        	CustTable� 	CustTable� 	CustGroup� formDataFieldStr���/// <summary>
/// This extendion of cust table modified method on cust group field
/// </summary>
[ExtensionOf(formDataFieldStr(CustTable,CustTable,CustGroup))]
final class CustTable_CustGroupModIRD_Extension
{
}   � 
modified�  � �#CustTable_CustGroupModIRD_Extension�� ! Mpublic final class Students
{
    str name = "John";
    int age =10;

}   " name  �" age  �   � 
main   � _args Args��  � �� 
parmName�   � �� 
parmAge�   � �Students�� ! Uinternal final class Ird_CustHoldService extends SysOperationServiceBase
{
       }SysOperationServiceBase   � 
process   � 	_contract Ird_CustOnHoldContract��  � �� 
clearInterface�  ��Ird_CustHoldService�� ! -internal final class IrdCrossCompDemo02
{
}   � 	
main   � _args Args��  � �IrdCrossCompDemo02�� !     ExtensionOf        HcmGoal� HcmGoal� � formDataSourceStr��b[ExtensionOf(formDataSourceStr(HcmGoal,HcmGoal))]
internal final class IrdHCMGoal_Extension
{
}   � 
GoalDisplay�   � �IrdHCMGoal_Extension�� ! &public final class Demo_ArgClass
{
}   � 	
main   � _args Args��  � �Demo_ArgClass�� !     ExtensionOf        	CustTable� � � tableStr��V[ExtensionOf(tableStr(CustTable))]
internal final class CustTable_Ird_Extension
{
}   � 
modifiedField   � _fieldId FieldId��  � �CustTable_Ird_Extension�� !     DataContractAttribute�x[DataContractAttribute]
internal final class Ird_CustOnHoldContract
{
    date fromdate, todate;
    NoYes debug;
}   " fromdate  �" todate  �" debug NoYes�   �     
Datamember� SysOperationLabel    "From Date"�� SysOperationDisplayOrder    "1"��
parmFromdate   � fromdate	_fromdate  ��   � ��     
Datamember� SysOperationLabel    	"To Date"�� SysOperationDisplayOrder    "2"��

parmTodate   � todate_todate  ��   � ��     
Datamember� SysOperationLabel    "Debug"�� SysOperationDisplayOrder    "3"��
	parmDebug   � debug_debug NoYes��  NoYes� �Ird_CustOnHoldContract�� !     ExtensionOf        SpeakersForm� ird_speaker� � formDataSourceStr��p[ExtensionOf(formDataSourceStr(SpeakersForm,ird_speaker))]
internal final class SpeakerForm_COC_Extension
{
}   � 
init�  � �SpeakerForm_COC_Extension�� !     BusinessEvents        IrdSalesConfBusEventContract� � � classStr� "SalesconfPost"� ""Sales confirmation posting event"�     
SalesOrder�	 ModuleAxapta���/// <summary>
/// This class is for adding the processing logic of business event
/// </summary>
/// 
[BusinessEvents(classStr(IrdSalesConfBusEventContract),"SalesconfPost","Sales confirmation posting event",ModuleAxapta::SalesOrder)]
public final class IrdSalesConfBusinessEvent extends BusinessEventsBase
{
    private SalesTable  salesTable;



}BusinessEventsBase   " 
salesTable 
SalesTable	  �   � 
parmSalestable   � _salesTable 
SalesTable��  
SalesTable��� 	
newFromSalestable   � _salesTable 
SalesTable��  IrdSalesConfBusinessevent� �� 
new�  ���     	Wrappable     True�� Hookable     True��
buildContract�  BusinessEventsContract� �IrdSalesConfBusinessEvent�� ! Sinternal final class IrdWoStatusUpdateService extends SysOperationServiceBase
{
}SysOperationServiceBase   � 
process   � 	_contract IrdWOStatusUpdateContract��  � �IrdWoStatusUpdateService�� ! ,internal final class IrdQueryclassdemo
{
}   � 	
main   � _args Args��  � �� 
myqueryclass�  � �IrdQueryclassdemo�� ! q///
///<summary>find method test class</summary>
///
internal final class Ird_speakerTab_findMethodCheck
{
}   � 	
main   � _args Args��  � �Ird_speakerTab_findMethodCheck�� ! �public final class PopulateDataToTables
{
    /// <summary>
    /// Class entry point. The system will call this method when a designated menu 
    /// is selected or when execution starts and this class is set as the startup class.
    /// </summary>
    /// <param name = "_args">The specified arguments.</param>
    /// 

    
    

}   � 	
main   � _args Args��  � �PopulateDataToTables�� !     ExtensionOf        EntAssetObjectTable� � � formstr���[ExtensionOf(formstr(EntAssetObjectTable))]
public final class Ird_EntAssetObjectTable_F_Extension
{
    /*public  void init()
    {
        next    init();

        FormStringControl   fsc = this.design().controlName(formControlStr(EntAssetObjectTable,ObjectTable_Ird_structureCode));
        fsc.registerOverrideMethod(methodStr(FormDataObject, lookup),formMethodStr(EntAssetObjectTable,overridenAssetStructureLookUp));

    
    }*/

    /*public void overridenAssetStructureLookUp(FormStringControl _formStringControl)
    {
        FormRun fr = this as FormRun;
        FormDataSource  fds = fr.dataSource(formDataSourceStr(EntAssetObjectTable,ObjectTable));
        EntAssetObjectTable entassetObjectTable = fds.cursor();
        //entAssetObjectTable.ModelYear= int2Str(year(today()));
        SysTableLookup  sysTableLookUp = SysTableLookup::newParameters(tableNum(Ird_AssetStructure),_formStringControl);
        Query   query   =new    Query();
        QueryBuildDataSource qbds = query.addDataSource(tableNum(Ird_AssetStructure));
        QueryBuildRange range = qbds.addRange(fieldNum(Ird_AssetStructure,Ird_structureCode));
        //range.value("Basement");
        range.value(EntAssetObjectType::find(entassetObjectTable.ObjectType).Ird_structureCode);
        sysTableLookUp.addLookupfield(fieldNum(Ird_AssetStructure,Ird_structureCode));
        sysTableLookUp.parmQuery(query);
        sysTableLookUp.performFormLookup();
    }*/
    
}#Ird_EntAssetObjectTable_F_Extension�