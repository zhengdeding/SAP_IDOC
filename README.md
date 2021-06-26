# SAP_IDOC

SAP ALE IDOC Quick Reference Guide


# Main Transaction Codes

## Main Menus

WEDI EDI Related Activities

BALE ALE Related Activities

SWLD Workflow Related Activities

SALE ALE Configuration

NACE Message Control Configuration


## IDOC Definition

SE11 Data Dictionary

WE30 IDoc type editor

WE31 Segment editor

BD53 Reduction of IDoc types

WE60 Documentation for IDoc types

WE61 Documentation for IDoc record types


## IDOC Monitoring

WE02 IDoc display

WE05 IDoc Lists

WE06 Active IDoc monitoring

WE07 IDoc statistics


## Configuration(ALE and EDI)

BD54 Maintain logical systems

BD64 Maintain distribution model

BD71 Distribute Customer Model

BD82 Generate partner profiles

FILE Logical File Paths

PFTC Task Definition

PPOC Maintain Organization Structure

SM59 Maintain RFC Destinations

SWE2 Event Linkage

SWU3 Basic Workflow Settings

WE20 Partner profiles

WE21 Port definition


## Run Time Workflow

SO01 SAP Inbox

SWEL Event Log

SWI1 Workflow Log

SWI2 Work Item Analysis

SWI5 Workload Analysis


## Message Control

NACE Condition Record Maintenance

VOK2 SD Message Control Components

VOK3 Purchasing message Control Components

VOFM View Message Requirements

V/86 Condition Table Field Catalog

WE15 IDoc test: Outbound from MC


## Testing

WE19 Test tool

WE12 IDoc test: Inb. Procg of Outb. File

WE16 IDoc test: Inbound File

WE17 IDoc test: Inbound status report

Reprocessing IDOCS

BD87 Process inbound IDocs

BD88 Process outbound IDocs


## System Monitoring

SM12 Locked Entries

SM13 Update Monitoring

SM21 System Log Display

SM58 Transactional RFC Log

SM66 Debug Async Update Tasks

ST22 Dump Analysis


## Transaction Codes of Interest

AL05 Monitor current workload

AL11 Display SAP Directories

AL18 Local File System Monitor

AL19 Remote File System Monitor

AL21 ABAP Program analysis

ALO1 Data Relationship Browser

ANA_VAR Table Analysis: Analysis Variants

BA10 Subsystem Config.

BA11 Channel Definition for Transceiver

BD10 Send Material

BD100 IDoc display object channel view

BD101 Consistency check

BD102 Outbound registry

BD103 Inbound registry

BD104 maintain tbd53

BD105 maintain tbd54

BD11 Fetch Material

BD12 Send customer

BD13 Open customer

BD14 Send vendor

BD15 Open vendor

BD16 Send Cost Center

BD17 Get Cost Center

BD18 Send General Ledger Account

BD19 Get General Ledger Account

BD20 IDoc passed to application

BD21 Select change pointer

BD22 Delete change pointers

BD23 Delete serialization data

BD24 Send Cost Elements

BD25 Send Activity Type

BD26 Get Activity Type

BD27 Send cost center activity prices

BD28 Send obj/cost element control data

BD30 Distribute material object list

BD31 Distribute document object list

BD32 Distribute plant allocations(matBOM)

BD40 Read change pointer for group

BD41 Dispatch IDocs for group

BD42 Check IDocs for group

BD43 Post IDocs for group

BD44 Assign message types to ser. group

BD47 Dependencies between methods

BD48 Dependency method - message

BD50 Activ. change pointer for mess.type

BD51 Maintain function modules (inbound)

BD52 Activ.change pointer per chng.doc.it

BD53 Reduction of IDoc types

BD55 Maintain IDoc conversion

BD56 Maintain IDoc segment filtering

BD57 Maintain link and serialization ty.

BD58 Convert Org. units

BD59 Allocation object type -> IDoc type

BD60 Additional data for message type

BD61 Activate change pointer

BD62 Define segment conversion rule

BD63 Transport ALE tables to message type

BD65 Maintain IDoc type required fields

BD66 IDoc type field -> change doc.field

BD67 Maintain input methods

BD68 Maintain lists

BD69 Assign message type to IDoc

BD70 Adjust number ranges

BD72 Activate events

BD73 Reposting of IDocs (ALE)

BD75 Convert IDoc status

BD76 Model upload/download monitoring

BD77 Distribution of control data

BD78 Monitoring control data distribution

BD79 Maintain IDoc conversion rules

BD80 Conversion pre-production/production

BD81 Filter objects parameter filtering

BD83 Send IDocs after an ALE error

BD84 Post IDocs after ALE error

BD85 Consistency check for transfer

BD86 Consistency check for sales

BD89 Control data model. - initial screen

BD90 Start DA-OU

BD91 Send characteristic

BD92 Send class

BD93 Send classification

BD94 OA - file transfer

BD95 Specify ALE object types

BD96 filter objects of receiver determin.

BD97 Assign RFC dest. to logical systems

BD98 ALE consistency check active

BD99 Message type dependencies

BDA1 Call RSARFCEX

BDA4 Specify ALE object types

BDA5 Distribute documents

BDBG Generate ALE interface (BAPI)

BDBP Hierarchy maintenance of BAPI param.

BDBS Generate coding for mapping

BDCP Number range maintenance: ALE_CP

BDLS Mapping Logical System Names

BDM2 Monitoring: IDocs with receiver

BDM5 Consistency check

BDM6 Monitor: Check input workflow

BDM7 ALE Audit: statistical analyses

BDM8 ALE Audit: Sending the confirmations

BDM9 Reorganizing the audit database

BDMC Upload info structures

BDR1 Display application log for recovery

BDR2 Reorganization of recovery data

BDRC ALE: Determine recovery objects

BDRL ALE: Process recovery objects

OE2C Process Code Inbound

OYE0 EDI: Maintain Port Def. arfc

OYE3 Display EDI Ports

OYE4 Display ALE Ports

OYED Maintain Port Definitions

OE3C System Process Code

OE1C Process Code (OutB)

OYEL Display EDP21 (InB Partner Profile)

OYEX Create EDP21 (InB Partner Profile Overview)

OYEH Display EDP12 (Msg Control)

OYER Create EDP12 (Msg Control Overview)

OYEI Display EDP13 (OutB Partner Profile)

OYEU Create EDP13 (OutB Partner Profile overview)

OYSM Number Range Port Definition

OYSN Number Range For IDOCS

OYSO Number Range IDOC Types

WE08 EDI: File Processing Status (EDFI2)

WE09 IDoc lists enhanced

WE10 IDoc lists enhanced

WE14 IDoc test: Outb. from IDoc

WE30 IDoc type editor

WE32 View editor

WE33 Value tables for IDoc documentation

WE40 System process codes

WE41 Process codes, outbound

WE42 Process codes, inbound

WE43 Funct.module: Status record display

WE44 Partner Types and selection reports

WE45 Forward (inbound) (V3, EDILOGADR)

WE46 IDoc administration

WE47 Status Maintenance

WE48 Inbound process codes: Texts

WE49 Inbound process codes: Change texts

WE50 System process codes: Texts

WE51 System process codes: Change texts

WE52 Outbound process codes: Texts

WE53 Outbound process codes: Change texts

WE54 FMs for changing file names

WE55 FMs for path names

WE56 Status process codes

WE57 Messages and application objects

WE58 Status process codes: Texts

WE59 Change status process codes

WE62 Documentation for segments

WE63 Parser for IDoc types and rec.types

WE70 Conversion: Basic types

WE71 Conversion: Extensions

WE72 Conversion: IDoc types

WE73 Conversion: Logical messages

WE80 IDoc types: Overview

WE81 Logical message types

WE82 Assignment IDoc type - Message

WE83 Extensions: Overview (EDCIM)

WE84 Assignment of IDoc and appl. fields

WECP Display CPIC interface status (R/2)

WEL0 Forward (inbound) (EDILOGADR)

WEL1 EDI: Interface Invoice for EDILOGADR

WENA Messages on basis of changes


## WorkFlow Configuration

OOAW & SWLV Subordinate And Peer Definition

PFAC Standard Roles

PO13 Maintain Substitutes

SWO1 Business Object Builder


## Code Task Number Description

EDIM TS00007988 No IDOC Created Yet

EDIO TS00007989 Error In Outbound Process

EDIX TS00008070 Syntax Error Outbound

EDII TS00008068 Error In Inbound Process

EDIY TS00008074 Syntax Error Inbound

EDIS TS00000078 Error in SubSystem

(Maintained in WE40)



## IDOC Xref–SAP / ANSI X.12 / EDIFACT


| 一个普通标题 | 一个普通标题 | 一个普通标题 |
| ------ | ------ | ------ |
| 短文本 | 中等文本 | 稍微长一点的文本 |
| 稍微长一点的文本 | 短文本 | 中等文本 |


| 一个普通标题 | 一个普通标题 | 一个普通标题 |
| ------ | ------ | ------ |
| 短文本 | 中等文本 | 稍微长一点的文本 |
| 稍微长一点的文本 | 短文本 | 中等文本 |


|IDOC |Msg |ANSI |EDIFACT |I |O|
| ------ | ------ | ------ | ------ | ------ | ------ |
|PEXR2001 |CREADV |812 |CREADV |X |X|
|PEXR2002 |CREADV |812 |CREADV |X |X|
|PEXR2001 |DEBADV |812 |DEBADV |X |X|
|PERX2002 |DEBADV |812 |DEBADV |X |X|
|DELFOR01 |DELINS |830 |DELFOR |X |X|
|DELFOR01 |DELINS |862 |DELJIT |X |X|
|DELVRY01 |DESADV |856 |DESADV |X |X|
|FINSTA01 |FINSTA | |FINSTA |X| |
|GSVERF01 |GSVERF |861|  |X |X|
|INVOIC01 |INVOIC |810 |INVOIC |X |X|
|INVOIC01 |INVOIC |880 |INVOIC |X |X|
|FINSTA01 |LOCKBX |823 | |X||
|ORDERS01 |ORDCHG |860 |ORDCHG |X |X|
|02, 03, 04 |ORDCHG |860 |ORDCHG |X |X|
|ORDERS01 |ORDCHG |876 |ORDCHG |X |X|
|02, 03, 04 |ORDCHG |876 |ORDCHG |X |X|
|ORDERS01 |ORDERS |850 |ORDERS |X |X|
|02, 03, 04 |ORDERS |850 |ORDERS |X |X|
|ORDERS01 |ORDERS |875 |ORDERS |X |X|
|02, 03, 04 |ORDERS |875 |ORDERS |X |X|
|ORDERS01 |ORDRSP |855 |ORDRSP |X |X|
|02, 03, 04 |ORDRSP |855 |ORDRSP |X |X|
|ORDERS01 |ORDRSP |865 |ORDRSP |X |X|
|02, 03, 04 |ORDRSP |865 |ORDRSP |X |X|
|PEXR2001 |PAYEXT ||PAYEXT ||X|
|PRICAT01 |PRICAT |832 |PRICAT ||X|
|PRICAT01 |PRICAT |879 |PRICAT ||X|
|PRICAT01 |PRICAT |888 |PRICAT ||X|
|PRICAT01 |PRICAT |889 |PRICAT ||X|
|PROACT01 |PROACT |852 |PROACT |||
|ORDERS01 |QUOTES |843 |||X
|02, 03, 04 |QUOTES |843 |||X
|PEXR2001 |REMADV |820 |REMADV |X |X|
|PEXR2002 |REMADV |820 |REMADV |X |X|
|ORDERS01 |REQOTE |840 |REQOTE |X |X|
|02, 03, 04 |REQOTE |840 |REQOTE |X |X|
|DELVRY01 |SHPCON |945 ||X||
|SHPMNT01 |SHPMNT |856 |IFTMIN ||X|
|02, 03 |SHPMNT |856 |IFTMIN ||X|
|SHPMNT03 |SHPMNT |204 |IFTMIN|||
|DELVRY01 |SHPORD |940 |||X|
|TXTRAW01 |TXTRAW |864 ||X||
|DELVRY01 |WHSCON |945 ||X||
|DELVRY01 |WHSORD |940 |||X|

##  Frequent General Transaction Categories

AL System Monitoring

BD EDI & ALE

CO Production Planning

DB Database

FB Vendors

IW Plant Maintenance

OL Config Related

OS Operating System Monitor

PA HR

RZ CCMS Monitoring

SA System Administration

SE Development

SM System Maintenance

SO SAPOffice

SP Spool

ST Performance and Tuning

SU Security

SW Workflow

VA Sales

WE EDI


## Programs of Interest

MSEIDOC2 IDoc Statistics 

MSEIDOC3 IDoc Lists 

MSESTA00 Status Maintenance (Tables TEDS!, TEDS2, TEDS3) via View 

RBDAGAI2 Re-Process of IDOCs after ALE input error 

RBDAGAIE ReProcess of edited IDOCs 

RBDAGAIN Re-Process incorrect IDOCs. (OutB) 

RBDAPP01 IDoc InB Process ready for transfer 

RBDAUD01 Statistical analyses for the ALE Audit 

RBDAUD02 Reorg audit DB - deleting table entries 

RBDAUTHI Include that contains all Auth checks 

RBDAUTHO Check Auths 

RBDCCMS1 IDocs for aRFC 

RBDCHECK Check IDOC Structure Against DB Tables 

RBDCICO1 Monitoring Via Checkin/Checkout For The ALE Customer Model 

RBDCNST2 Constants for Consist. Check 

RBDCPCLR Delete Change Pointers 

RBDCREO Reorg Batch Input Session Logs 

RBDCSUB Release BDC Sessions 

RBDCUS01 Direct Customer Model Maintenance 

RBDCUS02 Transport of ALE Tables for a Msg Type 

RBDCUS03 X-System Comparison of Number Range Objects 

RBDCUS04 Sending Model to Logical Systems 

RBDCUS15 Generating the partner profiles 

RBDCUS16 Data: Generating The Partner Protocols 

RBDCUS17 Routines: Generating The Partner Protocols 

RBDCUS19 ALE Consist. Checking 

RBDCUS23 ALE Consist. Check: Transfer Between Two Systems 

RBDCUS24 Parameters for Report RBDCUS23 

RBDCUS25 Interface control for RBDCUS23 

RBDCUS26 ALE Consist. Check: Create Purchase Order from Sales Order 

RBDCUS27 Data: Consist. Checking for SD Scenario 

RBDCUS28 Routines: Consist. Checking for SD Scenario 

RBDCUS31 Complete view of the Msg flow from view of one system. 

RBDCUS33 Changing the Call Parameters for DA-OU 

RBDCUS34 ALE Consist. Check 

RBDCUS35 Modelling the control data distribution 

RBDDATTR Upload/Download Data from the Org. Architect via Files 

RBDEVACT Activate Events for ALE/EDI 

RBDFECLF Fetch Classifications 

RBDFECRE Request Get Vendor Data 

RBDIDOCA Object Type IDOC: EDI IDOC 

RBDIDOCR IDOC Reduction 

RBDINPUT Process of incoming IDOCs. 

RBDMANIN Start Error Handling for Non-posted IDOCs 

RBDMIDOC Generate IDoc type from change pointers 

RBDMMSD1 Consist. Check: Reassignment Between Two Systems 

RBDMOIN1 IDoc list 

RBDMOIN2 IDoc display 

RBDMOIN3 IDoc overview 

RBDMOIN4 Time Distribution of IDOC Creation 

RBDMOIN5 Statuses Reached 

RBDMOIN6 Detailed Data on IDoc status 

RBDMOIN7 Check: Customer model definitions <--> Partner profiles 

RBDMOIN8 X-system IDOC Reporting 

RBDMOIN9 X-system Analysis Whether IDOC Dispatch is Possible 

RBDMOINB Display: IDoc in sending system ==> IDoc in receiving system 

RBDMOINC Consist. check for input 

RBDMOIND Status Conversion for Successful RFC Execution

RBDMOINF Consist. check for workflow for ALE/EDI InB error Process 

RBDMOINM Model upload/download monitoring 

RBDOUTPU Process outgoing IDOCs 

RBDPARPR Conversion of process codes in existing partner protocols 

RBDPRFTB Value Tables for a Msg Type 

RBDPROSE Converting ALE Settings for Productive Operation 

RBDRCCLR Reorganization of data in recovery objects 

RBDRCLOG Display Appl log of recovery process 

RBDRCOBJ ALE: Process recovery objects 

RBDREO01 Reorganize Long-Term Links 

RBDSALE Msg output, that SALE no longer exists 

RBDSALE1 Call of ALE IMG 

RBDSDMM1 Consist. Check: Create Purchase Order From Sales Order 

RBDSECRE Send creditor data 

RBDSEDEB Customers - send 

RBDSTATE Sending Confirmations For The ALE Audit 

RBDSYNEI Continue Process IDoc despite syntax error (InB) 

RBDSYNEO Continue Process IDoc despite syntax error (OutB) 

RBDSYNER Process IDoc despite syntax error 

RBDTABCO Table Analyses 

RBDTBD22 Mapping between change document and IDoc 

RBDTBD23 Required IDoc fields 

RBDTBDA1 Activate Change Pointer 

RBDTRAN1 Generates transport requests for ALE control data distribution 

RBDTRAN2 Monitoring transport of control data 

RBDTRANS object type TRANSID: Transaction ID 

RBDTXT01 Text elements for customizing checks in distributed contracts 

RSEAUTPA INCLUDE RSEAUTPA: Central Routines for Auth. Check for 0EDS,0EDV,0EDY 

RSEBASIS EDI: INCLUDE for Alternative Structures and Access Routines 

RSEBIDOC Object Type IDOCBASIS: Basic IDOC 

RSEBSCHK EDI: Check System Type (Basis or Appl System)

RSECEDI1 EDI Constants/Exceptions 

RSECHK01 Test IDoc Type Segments for Consist. 

RSECHK02 IDoc Types: Consist. Check 

RSECHK03 IDoc Type Consist. Test 

RSECHK04 Break Down of IDoc Types into Segments 

RSECHK05 Evaluate Occurrences of IDoc Type Segments 

RSECHK07 Consist. Test for Partner Profiles 

RSECODIN IDoc: Display InB Process Codes 

RSECODOU IDoc: Display OutB Process Codes 

RSECODST IDoc: Display Status Process Codes 

RSECODSY IDoc: Display System Process Codes 

RSEIDC00 object type IDOCSYIDOC : Meta-IDoc 

RSEIDOC1 WF-EDI: Doc. record types 

RSEIDOC2 IDoc list 

RSEIDOC3 Doc. IDoc Record Types and IDoc Types (Parser) 

RSEIDOC4 WF-EDI: Doc. Segments 

RSEIDOC5 WF-EDI: Doc. IDOC Type 

RSEIDOC6 Doc. of IDoc Types (Overview) 

RSEIDOC7 WF-EDI: Information System 

RSEIDOCA Main Subprograms of the Program Group RSEIDOCx 

RSEIDOCB EDI Statistics - Extended Selection 

RSEIDOCC EDI Statistics - Error History 

RSEIDOCD IDoc Lists 

RSEIDOCE Detail Data on IDoc Status 

RSEIDOCF Time Distribution of IDoc Creation 

RSEIDOCG EDI: Convert current status in IDOCs 

RSEIDOCI INCLUDE for List Formatting 

RSEIDOCL Global form routines for IDoc display 

RSEIDOCM CA-EDI: Active monitoring for IDoc Process 

RSEINB00 InB Process of IDOCs (EDI) 

RSEINB10 SAP-IDoc: Receiving IDocs from an R/2 System via CPI-C 

RSEINB11 IDoc InB: Transfer of IDocs from an R/2 System to the Appl 

RSEINB50 IDoc Inbox: Activate inbox and process IDocs with status '50' 

RSEINBDT EDI InB Process (Global Data Declaration) 

RSEINBEV IDoc InB: Customizing - Activate event-event receiver coupling

RSEINBF0 EDI InB Process (FORM Routines) 

RSEINBF1 EDI InB Process (Other FORM Routines) 

RSEINBT1 Include RSEINBT1 

RSELINKD Call display method for object 

RSELOGAD EDI: Selection of Maintenance Interface for EDILOGADR 

RSEMASSA EDI: Mass Activation of Partner Profiles 

RSEOSTAT Object Type STATRECORD : Status Record 

RSEOUT00 Process All Selected IDOCs (EDI) 

RSEPCON1 Print Control Record of an IDOC 

RSEPDAT1 Print a Data Record of an IDOC 

RSEPDATA Print all Status Records of an IDOC 

RSEPORTA IDoc: Tree display EDI and ALE ports 

RSEPSEGA Print List of all SAP Segments of an IDOC 

RSEPSTA1 Print a Status Record of an IDOC 

RSEPSTAA Print all Status Records of an IDOC 

RSEREPSG Repair IDoc Segments 

RSESTA00 InB Process of Status Records (EDI)

RSESTA02 object type IDOCSTATUS : Status record 

RSESTA11 IDoc: Sending status records for InB IDocs to R/2 System 

RSESTADT EDI InB Process (Global Data Declaration) 

RSESTAF0 EDI InB Process (FORM Routines) 

RSESTAF1 EDI InB Process (Other FORM Routines) 

RSESTAT1 Print a Status Record of an IDOC 

RSESTATA Print all Status Records of an IDOC 

RSETESTP Report for Test for Existence of Master Data 

RSETEXT0 Object Type IDOCTXTRAW: Text Msg 

RSEXARCA Archiving IDocs 

RSEXARCB IDoc archiving periodic implementation in background 

RSEXARCD Delete Archived IDocs 

RSEXARCL Reload Program IDoc Archive 

RSEXARCR IDoc Archive Read Program 

RSIDOCAM object type IDOCSTATIS : IDoc statistics 

RSIDOCWF Object Type IDOC: EDI IDOC 

RSNAST00 Process NAST Table Entries 

RSNASTED Analysis of NAST Record for Output Type 6 (EDI) 

SAPMSED0 WF-EDI: Maintain Partner Profiles 

SAPMSED2 WF-EDI: Interface for Test Environment 

SAPMSED3 EDI: IDoc - Segment Editor 

SAPMSED5 EDI: Development of IDoc Types 

SAPMSED7 IDoc: Test tool for IDoc InB Process 

SAPMSED8 IDoc Doc. tools menu


## Tables of Interest In EDI

ARCH_OBJ Objects for Archiving 

BDAUDQUEUE ALE Audit queue with not-processed IDOCs 

BDAUDSTATE Statistical key figures for the ALE Audit 

BDCP Chg pointer 

BDCPS Chg pointer: Status 

BDSER Serialization: last date of object at sender 

BTCUED User event IDs for background processing 

CDHDR Change document header 

CDPOS Change document items 

CIMHIS EDI: Predecessors of Ext Types 

CIMSYN Table for Syntax Desc of IDoc Type Exts 

EDADM EDI client-specific system parameters 

EDCIM EDI: Value Table for Cust. Ext Types 

EDCIMT EDI: Short Desc of Ext Types 

EDE1T EDI: Text table for OutB process codes 

EDE2T EDI: Text table for iInB process codes 

EDE5T EDI: Text table for error processing codes 

EDE6T IDOC: Text table for proc cds for iInB statuses 

EDFI2 EDI: Last processed Doc in file 

EDFIL EDI: Last processed Doc in file 

EDI_MONIT WF-EDI: Struc. for Dflt Values in EDI Mon 

EDI30C IDOCClusters 3.0C Onward 

EDI40 IDOC Records for 4.0 - 

EDICONFIG CA-EDI: Param tbl for user configuration 

EDID2 Data seg (IDOC) from 3.0C 

EDID2 IDOC segments (version 3.1) 

EDID3 Data seg table (EDI IDocs) from 3.0 

EDID4 IDOC segments (version 4.6) 

EDIDC Control record (EDI Intermediate Doc) 

EDIDC IDOC Control Records 

EDIDD Data seg (EDI Intermediate Doc) 

EDIDO Value table for IDoc types 

EDIDO Value table for IDoc types 

EDIDOT Short Desc of IDoc types 

EDIDOT Short description of IDoc types 

EDIDS IDOC Status Records 

EDIDS Status record (EDI IDoc) 

EDIE5 Assign log. addr to phys destination in SAP 

EDIFCT IDoc: Asgmnt of FM to log. Msg and IDoc type 

EDIFM IDoc: FMs for creating file names 

EDIFMT IDoc: Text table for EDIFM (funct. module for file names) 

EDILOGADR Assign logical address to physical destination 

EDIMAP EDI: Asgmnt Table Between IDoc and Application Flds 

EDIMSG EDI: Msg Types and Asgmnt to IDoc Types 

EDIMSGT Short Desc of SAP Msg types 

EDIPHONE CA-EDI: Telephony data for partner profiles 

EDIPO Table for Desc of ports for EDI 

EDIPOI Table for describing Internet ports 

EDISEG EDI: IDoc Type Segs with Asgmnt to Seg Type

EDISEGT EDI: Short Desc of Segs in EDSEA/EDISEG 

EDISYN Docation Table for Generated Syntax of IDoc Types 

EDIVAL Ref. From Check Table to Languagedependent Table 

EDMAT EDI: Texts for the 'Maturity Levels' in partner profile 

EDMSG Value table for SAP Msg types 

EDP12 EDI PP: OutB Table 2 (Find Process Code) 

EDP13 EDI PP: OutB Table 3 (Log. Msg) 

EDP21 EDI PP: IInB Table 1 (Find Code f. Process Type) 

EDPI1 EDI: Partner profiles (iInB) 

EDPO1 EDI table for partner profiles (OutB), level 1 

EDPP1 EDI PP: List of EDI Partners (IInB and OutB) 

EDSEA EDI: Table of all segs of current release 

EDSEG EDI: Convert segs to 3.0 

EDSVRS EDI: Table of all segs of current release 

EDSYN EDI: Convert IDoc type syntax to 3.0 

IDOCHIS EDI: Predecessor of basic IDoc types 

IDOCSYN CA-EDI: Syntax Desc for basis IDoc types 

IDOCVRS EDI: IDoc type versions created by Cust.s NAST Message Status 

TBD00 Cust. models 

TBD03 Communication relation between systems 

TBD10 Def., out of which IDOC Flds a filter object is to be read 

TBD12 Map Msg type -> serialization and link type 

TBD13 Org units to be converted in IDoc Flds 

TBD14 Msg type -> object type 

TBD20 ALE: data for IDOC projection filter 

TBD21 ALE: IDOC reduction 

TBD22 ALE: map IDOC-Flds to Chg Doc Flds 

TBD23 ALE: definition of mandatory segs/Flds 

TBD30 ALE: Conversion rules for IDOc segs 

TBD50 Msg-dependent attributes for IDOC input methods 

TBD51 Attributes of IDOC input function modules 

TBD52 Function modules for iInB ALE-EDI 

TBD62 Asgmnt of Chg Doc field to Msg type 

TBDA1 ALE active 

TBDA2 ALE Msg active 

TBDLI Listings for a logical system 

TBDLS Logical system 

TBDLST Text for logical system 

TBDLT Lists for a logical system for ALE distribution 

TBDME ALE supplement data for EDI Msg type 

TBDMS Asgmnt of Msg type to IDoc type for ALE 

TBDRCSTATE Objects in Recovery environment (ALE) 

TEDE1 EDI process types (OutB) 

TEDE2 EDI process types (iInB) 

TEDE3 Function module, which displays EDIDS record 

TEDE5 EDI Process codes for error handling 

TEDE6 IDOC process codes for iInB statuses 

TEDEF Assign proc. type to funct. module that processes proc. type 

TEDS1 IDoc status values 

TEDS2 Short Desc of IDoc status values 

TEDS3 EDI status values: Importance/qualification 

TEDST SAP EDI Form routines to read master data 

TEDTT EDI: Partner Types - Language-dependent Names 

TEDWL Channel definition for transceiver 

TEUDES Configuration of upload files 

TEUPL Configuration of upload files 

TEUPLT Name of configuration IDoc for transceiver 

TKANA Entries for channel definitions 

TKANAT Descs for channel definitions 

TNAPR Pgms for output. Pgm to SAPScript.


## IDOC Status Codes

00 Not used, only R/2 

01 IDoc created 

02 Error passing data to port 

03 Data passed to port OK 

04 Error within control information of EDI subsystem 

05 Error during translation 

06 Translation OK 

07 Error during syntax check 

08 Syntax check OK 

09 Error during interchange handling 

10 Interchange handling OK 

11 Error during dispatch 

12 Dispatch OK 

13 Retransmission OK 

14 Interchange Acknowledgement positive 

15 Interchange Acknowledgement negative 

16 Functional Acknowledgement positive 

17 Functional Acknowledgement negative 

18 Triggering EDI subsystem OK 

19 Data transfer for test OK 

20 Error triggering EDI subsystem 

21 Error passing data for test 

22 Dispatch OK, acknowledgement still due 

23 Error during retransmission 

24 Control information of EDI subsystem OK 

25 Processing despite syntax error (outbound) 

26 Error during syntax check of IDoc (outbound) 

27 Error in dispatch level (ALE service) 

28 Not used 

29 Error in ALE service 

30 IDoc ready for dispatch (ALE service) 

31 Error - no further processing 

32 IDoc was edited 

33 Original of an IDoc which was edited 

34 Error in control record of IDoc 

35 IDoc reloaded from archive 

36 Electronic signature not performed (timeout) 

37 IDoc added incorrectly 

38 IDoc archived 

39 IDoc is in the receiving system (ALE service) 

40 Application document not created in receiving system 

41 Application document created in receiving system 

42 IDoc was created by test transaction 

50 IDoc added 

51 Error: Application document not posted 

52 Application document not fully posted 

53 Application document posted 

54 Error during formal application check 

55 Formal application check OK 

56 IDoc with errors added 

57 Test IDoc: Error during application check 

58 IDoc-Copy from an R/2 connection 

59 Not used 

60 Error during syntax check of IDoc (inbound) 

61 Processing despite syntax error (inbound) 

62 IDoc passed to application 

63 Error passing IDoc to application 

64 IDoc ready to be transferred to application 

65 Error in ALE service 

66 IDoc is waiting for predecessor IDoc (serialization) 

67 Not used 

68 Error - no further processing 

69 IDoc was edited 

70 Original of an IDoc which was edited 

71 IDoc reloaded from archive 

72 Not used, only R/2 

73 IDoc archived 

74 IDOC was created by Test Transaction


## IDOC Types

|IDOC Type | Description |
| ------ | ------ |
| ABSEN1 |Attendance/Absence in CC1 |
| ACCONF01 |Conf. of IDoc processing from appl. |
| ACLPAY01 |Posting in acctng: InB invoice |
| ACLREC01 |Posting in acctng: Billing document |
| ACPJOU01 |Posting in acctng from Mat.s mgmt |
| ACTIV3 |Units in CC3 |
| ACTIV4 |Units in CC4 |
| ALEAUD01 |Conf.s of the processing status of InB IDocs |
| ALEREQ01 |General request - Basis IDoc type |
| BATCH5 |Batch in CC5 |
| BETMAS01 |Site Mstr. data Dist. ALE |
| BLAORD01 |Purchasing contracts |
| BLAORD02 |Purchasing contracts |
| BLAREL01 |Contract release order statistics |
| BOMDOC01 |Mstr. BOM - document |
| BOMMAT01 |Mstr. BOM - Mat. |
| BTC_ID01 |Process order with components |
| BTC_ID02 |Production Req from superior system |
| BTC_ID03 |Production commitment to superior system |
| CHRMAS01 |Mstr. characteristic basic data |
| CHRMAS02 |Mstr. attribute with object dependencies |
| CLFMAS01 |Mstr. object classification |
| CLSMAS01 |Mstr. class |
| CLSMAS02 |Dist. of classes with object dependencies |
| CMREQU01 |TR-CM: Invitation to TR-CM system to send data |
| CMSEND01 |TR/CM-IDOC: XFer of TR-CM data |
| CNPMAS01 |Mstr. configuration profile |
| COACOR01 |Core Mstr. activity type |
| COACTV01 |IDoc for cost center/activity type |
| COAMAS01 |Mstr. activity type |
| COCOKA01 |Control segment CO object/cost element |
| CODCMT01 |IDoc for a CO document |
| COELEM01 |Cost elements: Mstr. data Dist. |
| COGRP01 |IDoc for CO groups (e.g. cost center groups) |
| COND_A01 |Interchange of conditions: Mstr. data for price determ. |
| CONDAT01 |Change to customizing data |
| CONDA201 |ALE customizing Dist. add-on |
| CONF11 |Conf.s in CC1 |
| CONF21 |Conf.s in CC2, time events |
| CONF31 |Conf.s in CC3, time events |
| CONF32 |Conf.s in CC3, wage slips |
| CONF41 |Conf.s in CC4, time events |
| CONF42 |Conf.s in CC4, wage slips |
| CONF51 |CC5 Conf.s run schedules |
| COPAGN01 |CO-PA entry |
| COPCPA01 |XFer product costing CO-PC -> CO-PA |
| COSCOR01 |Core Mstr. cost center |
| COSMAS01 |Mstr. cost center |
| COTOTL01 |IDoc for CO totals records |
| CRECOR01 |Vendor Mstr. data Dist. ALE Core Mstr. data |
| CREMAS01 |Vendor Mstr. data Dist. ALE |
| DEBCOR01 |Core Mstr. - customer |
| DEBMAS01 |Customer Mstr. |
| DEBMAS02 |Customer Mstr. |
| DELFOR01 |Delivery schedule/JIT schedule |
| DES_ID01 |Shipping notification |
| DESADV01 |Shipping notification |
| DIFFE2 |Differences in CC2 |
| DIFFE3 |Differences in CC3 |
| DIFFE4 |Differences in CC4 ||
|DISTU2 |Reasons for problems CC2 |
|DOCMAS01 |Mstr. document |
|DOCMAS02 |Document 02|
|DWLOAD Dwnld transceiver configuration |
|EKSEKS01 |Purchasing document data for Purchasing Info System |
|EXPINV01 |Export Invoice IDOC (E.F.I.) |
|EXTWA1 |External wage types |
|FIDCCH01 |IDoc for FI document changes (dunning block) |
|FIDCCP01 |IDoc: Complete FI document |
|FIDCMT01 |IDoc for FI documents |
|GLCORE01 |Mstr. data G/L accounts: Core IDoc |
|GLDCMT01 |IDoc type for GLX rollups |
|GLMAST01 |Mstr. data G/L accounts: Max. IDoc |
|GSVERF01 |IDoc input credit memo procedure |
|HRMD_A01 |HR: Mstr. and Org. data (application system) |
|HRMD_B01 |HR: Mstr. and Org. data (basis system) |
|HRPAYP01 |HR - XFer FI/CO |
|HRPLL40 |Logistics Conf.s for HR Mgmt |
|HRTRVL01 |HR-TRV: XFer travel expenses FI/CO |
|IDCREF01 |Reference message as logical grouping for electron.signature |
|INFREC01 |Purchasing info record |
|INV_ID01 |Invoice |
|INVCON01 |Stock change data for inventory controlling |
|INVOIC01 |Invoice/Billing document |
|KNOMAS01 |Mstr. object dependencies basic data |
|LABELS00 |ISR labeling: label |
|LIS_EXTR |LIS InB interface for external data |
|LOCAT5 |Location in CC5 |
|LOIBOM01 |Mstr. bill of Mat. |
|LOICAL01 |Mstr. calendar |
|LOINUM01 |Number of IDocs sent |
|LOIPLO01 |Mstr. planned order |
|LOIPRO01 |Mstr. production order |
|LOIRNH01 |Mstr. hierarchy/networks |
|LOIROU01 |Mstr. routing |
|LOIRSH01 |Mstr. run schedule header |
|LOISTD01 |Mstr. Reqs/stock list |
|LOIWCS01 |Mstr. work center |
|MALFK5 |CC5 reasons for scrap |
|MATCOR01 |Core Mstr. Mat. |
|MATMAS01 |Mat. Mstr. |
|MATMAS02 |Mat. Mstr. |
|OPERA2 |Operations in CC2 |
|OPERA3 |Operations in CC3 |
|OPERA4 |Operations in CC4 |
|OPERS3 |Operation status in CC3 |
|OPERS4 |Operation status in CC4 |
|ORD_ID01 |Req.for quot./quotation/purchase order/order change |
|ORDERS01 |Purchasing/Sales |
|ORDERS02 |Purchasing/Sales |
|OSTAT2 |Process status CC2 |
|PEROP2 |Person reference to operation |
|PERSO1 |Personnel Mstr. records in CC1 |
|PERSO2 |Personnel Mstr. in CC2 |
|PERSO3 |Personnel Mstr. in CC3 |
|PERSO4 |Personnel Mstr. in CC4 |
|PEXR2001 |Payment/payment advice note/credit memo/debit advice |
|PKHD5 |CC5 kanban control cycles |
|PKPS5 |CC5 Kanban container |
|PKST5 |CC5 status for kanban container |
|PLANT3 |Plants in CC3 |
|PLANT4 |Plants in CC4 |
|REQUI2 |Conf. request in CC2 |
|REQUI3 |Conf. request in CC2 |
|REQUI4 |Conf. request in CC4 |
|REQUI5 |Conf. request in CC5 |
|SDPAID01 |Shipping element data Conf. to customer delivery |
|SDPIID01 |Picking data Conf. to customer delivery |
|SDPIOD01 |Picking notification to subsystem|
|SHPMNT01 |Transport |
|SISCSO01 |VIS - Sales order |
|SISDEL01 |VIS - delivery |
|SISINV01 |VIS - billing document |
|SOPGEN01 |General info structure Dist. |
|SRCLST01 |Source List |
|SRVMAS01 |Service Mstr. record with texts |
|SYIDOC01 |CA-EDI: Transport of IDoc types |
|SYNCHRON |Dummy IDoc type for synchronous communication |
|SYRECD01 |CA-EDI: Transport of IDoc record types |
|SYSTAT01 |CA-EDI: XFer from status records |
|TPSDLR01 |Selection via variant from external system |
|TPSDLS01 |Dispatch of delivery documents to shipping planning system |
|TPSLOC01 |Dispatch of location Mstr. data to transport planning syst. |
|TPSSHT01 |Dispatch of planned shipments from transport planning system| 
|TXTRAW01 |WF-EDI: XFerring free text to SAPoffice format 'RAW' |
|UNIMA2 |Alternative units of measure |
|UNIT2 |Units in CC2 |
|UNIT3 |Units in CC3 |
|UNIT4 |Units in CC4 |
|UPLOAD |Configuration transceiver for upload |
|VTAMAS01 |Mstr. variants table |
|VTMMAS01 |Mstr. maintenance table contents |
|WBB_ID01 |Source list: Product message (3.0A) |
|WBBDLD01 |Assortment list: Mat. data |
|WBBDLD02 |Assortment list: Mat. data (Rel. 4.0) |
|WGSREQ01 |Order receipt IS-R |
|WMBIID01 |Block Storage Bins |
|WMCAID01 |Reversal/Reversal request for XFer order |
|WMINID01 |Information text for link to subsystems |
|WMIVID01 |Enter count results |
|WMMBID01 |Goods movements for mobile data entry |
|WMRRID01 |Release reference number |
|WMSUID01 |Move storage unit |
|WMTCID01 |Confirm XFer order |
|WMTOID01 |Transport request |
|WMTRID01 |XFer Req |
|WORKC2 |Workcenters in CC2 |
|WORKC3 |Workcenters in CC3 |
|WORKC4 |Workcenters in CC4 |
|WP_EAN01 |POS interface: Upload/Dwnld EAN assignments |
|WP_PER01 |POS interface: Upload/Dwnld person data |
|WP_PLU01 |POS interface: Upload/Dwnld article Mstr. |
|WP_PLU02 |New segments in Mat. Mstr.: scales and discount in kind |
|WPDCUR01 |POS interface: Dwnld exchange rates |
|WPDNAC01 |POS interface: Dwnld products |
|WPDSET01 |POS interface: Dwnld set assignments |
|WPDTAX01 |POS interface: Dwnld tax rates |
|WPDWGR01 |POS interface: Dwnld Mat. group Mstr. |
|WPUBON01 |POS interface: Upload sales docs (trnsctns), non-aggregated |
|WPUERR01 |POS interface: Upload messages SRS/POS/SCS |
|WPUFIB01 |POS interface: Upload Fin.Acc. interface SRS/POS |
|WPUKSR01 |POS Interface: InB processing cashier data for POS stats |
|WPUTAB01 |POS interface: Upload day-end closing POS |
|WPUUMS01 |POS interface: Upload sales data (compressed) |
|WPUWBW01 |POS interface: Upload goods movements|





## User Exits and Enhancements



|IDOC |Dir |Enhancemnt |Description|
| ------ | ------ | ------ |------ |
|BLAOCH |IO |MM06E002| Contracts Change |
|BLAORD |IO |MM06E002| Contracts |
|BLAREL |IO |MM06E002| Contract Release |
|COND_A |O |VKOE0001 |Pricing Conditions |
|COND_A |I |VKOI0001| Pricing Conditions |
|CREMAS |IO |VSV00001| Vendor Master |
|DEBMAS |IO |VSV00001| Customer Master |
|DELINS |O |MM06E001| Scheduling Agreement |
|DESADV |I |MM06E001| Advance Shipment Notice |
|FIDCMT |IO |F050S001| Distrib. Genl. Ledger |
|INFREC |O |MMAL0003| Purchasing Info Rec |
|INFREC |I |MMAL0004| Purchasing Info Rec |
|INVOIC |O |LVEDF001| Invoices |
|INVOIC |I |FEDI0001| FI Invoices |
|MATMAS |IO |MGV00001| Material master |
|ORDCHG |O |MM06E001| Purch. Ord. Change |
|ORDCHG |I |VEDB0001| Sales Ord. Change |
|ORDERS |O |MM06E001| Purchase Orders |
|ORDERS |I |VEDA0001| Sales Orders |
|ORDRSP |O |SDEDI001| Order Confirmation |
|ORDRSP |I |MM06E001| Order Response for Purchase Order |
|PAYEXT |I |FEDI0002| Payment Order |
|PAYEXT |O |FEDI0003| Payment Order |
|REMADV |I |FEDI0002| Remittance Advice |
|REMADV |O |FEDI0003| Remittance Advice |
|REQOTE |I |VEDQ0001| InB Req for Quote |
|SDPACK |I |VMDE0001| Err Handling Input IDOC |
|SDPACK |I |VMDE0004| Packing |
|SDPICK |I |VMDE0001| Err Handling Input IDOC |
|SDPICK |O |VMDE0002| Picking |
|SDPICK |I |VMDE0003| Picking |
|SRCLST |O |MMAL0001| Source List |
|SRCLST |I |MMAL0002| Source List |
|SRVMAS |O |BASO0001| Service Master |
|SRVMAS |I |BASI0001| Service Master |
|WMBBIN |I |MWMIDI01| Err Handling Input IDOC |
|WMBBIN |I |MWMINI04| Block Storage Type |
|WMCATO |I |MWMIDI01| Err Handling Input IDOC |
|WMCATO |I |MWMIDI03| Cancel Req Transfer Ord |
|WMCATO |O |MWMIDO02| Cancel Req Transfer Ord |
|WMINVE |I |MWMIDO07| Err Handling Input IDOC |
|WMINVE |I |MWMIDO09| Count Data Inventory |
|WMINVE |O |MWMIDO04| Count Data Inventory |
|WMMBXY |I |MWMIDO07| Err Handling Input IDOC |
|WMMBXY |I |MWMIDO08| Goods Movement |
|WMRREF |O |MWMIDO03| Release Reference Numb |
|WMSUMO |I |MWMIDI01| Err Handling Input IDOC |
|WMSUMO |I |MWMIDI06| Move Storage Unit |
|WMTOCO |I |MWMIDI01| Err Handling Input IDOC |
|WMTOCO |I |MWMIDI02| Confirm Transfer Order |
|WMTORD |I |MWMIDO07| Err Handling Input IDOC |
|WMTORD |I |MWMIDO10| Create Transfer Order |
|WMTORD |O |MWMIDO01| Create Transfer Order |
|WMTREQ |I |MWMIDI01| Err Handling Input IDOC |
|WMTREQ |I |MWMIDI05| Create Transfer Request |
|ORDERS |I |LVEDAF0U| Sales Order |
|ORDCHG |I |LVEDBF0U| Sales Order Change ||
|DESADV |O |LVED2FZZ| Advanced ShippingNotice|
