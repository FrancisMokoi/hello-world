hello world

hi team,

francis here, I worked as a scheduling officer with a security company
I am trying to do leave scheduling using scpript and its something new to tab into this world
I had tried using macros as a new begining to start with and that gave me a very strong mood to write something in script
I had this part created using macros and to go wide write up srcript is a challenges to me at the moment.
need your advise and input

macros.js
/** @OnlyCurrentDoc */

function EmployeeName() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function EmployeeNo() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function LeaveType() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function Units() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function NotifiedDate() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function FromDate() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function ToDate() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function FollowupDate() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function ExpectedReturnDate() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function RequestedLeaveUnits() {
  var spreadsheet = SpreadsheetApp.getActive();
};

function FormText() {
  var spreadsheet = SpreadsheetApp.getActive();
  spreadsheet.getActiveRangeList().setFontColor('ACCENT6');
  spreadsheet.getCurrentCell().offset(0, 1).activate();
  spreadsheet.getActiveRangeList().setBackground('#d5a6bd');
  spreadsheet.getCurrentCell().offset(0, 1).activate();
  spreadsheet.getActiveRangeList().setFontColor('#b6d7a8');
  spreadsheet.getCurrentCell().offset(0, 2).activate();
  spreadsheet.getActiveRangeList().setFontColor('ACCENT5');
  spreadsheet.getCurrentCell().offset(0, 1).activate();
  spreadsheet.getActiveRangeList().setFontColor('ACCENT4');
  spreadsheet.getCurrentCell().offset(0, 1).activate();
  spreadsheet.getActiveRangeList().setFontColor('ACCENT6');
  spreadsheet.getCurrentCell().offset(0, 1).activate();
  spreadsheet.getActiveRangeList().setBackground('ACCENT3');
  spreadsheet.getCurrentCell().offset(0, 1).activate();
  spreadsheet.getActiveRangeList().setFontColor('ACCENT5');
  spreadsheet.getCurrentCell().offset(0, 1).activate();
  spreadsheet.getActiveRangeList().setBackground('ACCENT6')
  .setFontColor('ACCENT6')
  .setBackground(null);
  spreadsheet.getCurrentCell().offset(0, -2).activate();
  spreadsheet.getActiveRangeList().setBackground(null)
  .setFontColor('ACCENT4');
  spreadsheet.getCurrentCell().offset(0, -6).activate();
  spreadsheet.getActiveRangeList().setBackground(null)
  .setFontColor('ACCENT5');
  spreadsheet.getCurrentCell().offset(8, 6).activate();
};
