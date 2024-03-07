# DMS Features List

```
1. Projects
a. Add New Project
b. Rename Project
c. Archived Project
d. Restore Project
e. Delete Project
f. Copy Data To Project Task Board
g. Archived Project List
h. Project wise Task Board
i. Developers Note:
i.Model: Project.php
ii.View: admin.boards.index
iii.Controller: BoardController.php
iv.Methods: index , createProject, updateProject, restoreProject,
deleteProject
```

Task Boards
aAdd New Board
bEdit Board
cAssign Multiple Data Group
dClient List
eArchived Board
fRestore Board
gDelete Board
hAssign Members to Board
iTask Board Move to Another Project  Edit Board)
jArchived Board List
kBoard Preview  Kanban
lDevelopers Note:
iModel: Board.php
iiView: admin.boards.kanban
iiiController: BoardController.php
ivMethods: boards , createBoard, updateBoard, restoreBoard,
deleteBoard, addMemberBoard, renderBoardMember,
assignDataGroup
Task List
aAdd New List to Task Board
bRename List
cSort List
dArchived Project List
eSort Tasks to the List
fImport Clients to the List


gDevelopers Note:
iModel: BoardList.php
iiView: admin.boards.kanban
iiiController: BoardController.php
ivMethods: createList , updateList, deleteList, sortList,
importProjectClients
Tasks
aAdd New Task
bRename Task Title
cNotifications
dStatus Assign Dynamic)
ePriority Assign Dynamic)
fSet Start Date & Time
gSet Due Date & Time
hLabels Create
iLabels Assign
jLabels Delete
kDescription with Editor
lPost Comments with Editor
mDelete Comments
nAttachment Create with Title
oAttachment List in Task Window
pAttachment: Download  View
qSend Message through Respon.io Channel.
rSend Email through Respon.io Channel.
sOpen Respond.io Conversation


tRespond.io to DCMS Task window linkup Automatic Task window Open)
uCopy Task Link & Share
vMove Task to another Board
wArchive/Delete Tasks
xSet Reminder Notification
yShow Reminders in Dashbaord
zNavigate Client Details from the Task window
aaActivity Log
abShow total comments & attachment data for the task
acDrag & Drop task one list to another list
adSort Tasks
aeSwitch Board List Project Wise
afDevelopers Note:
iModel: BoardCard, BoardCardAttachment, BoardCardComment,
BoardCardLabel, TaskReminder, BoardCardMember
iiView: admin.boards.kanban
iiiController: BoardController.php
ivMethods: createCard , sortCard, renderCards, renderCardInfo ,
renderCardPrimaryInfo, updateCardDragOtherBoard,
updateCardDragSameBoard, updateLabel, renderCardDates,
updateTaskDates, moveTask, storeAttachment
Cometchat Integration
Project Management
aStatus Management
iCreate Status with Color Code
iiEdit Status
iiiDelete Status


ivDevelopers Note:
Model: CardStatus
View: admin.boards.status
Controller: BoardController
Methods: status, createStatus, deleteStatus, updateStatus
bPriority Management
iCreate Priority with Color Code
iiEdit Priority
iiiDelete Priority
ivDevelopers Note:
Model: CardPriority
View: admin.boards.priority
Controller: BoardController
Methods: priority, createPriority, deletePriority, updatePriority
Quotes
aAdd Quotes
bEdit Quotes
cDelete Quotes
dPublished/Draft Quotes
eShow Quotes in Dashbaord
fDevelopers Note:
iModel: Quotes
iiView: admin.boards.quotes.index
iiiController: BoardController
ivMethods: quotes, createQuotes, deleteQuotes, updateQuotes
Notice Board


aAdd Notices
bEdit Notices
cDelete Notices
dPublished/Draft Notices
eShow Notices in Dashboard
fDevelopers Note:
iModel: NoticeBoard
iiView: admin.boards.notices.index
iiiController: BoardController
ivMethods: notice, createNotice, deleteNotice, updateNotice
Access Management
aProject Management
iCopy Client to Project
iiProject Settings
bProjects
aShow Project Tab
bShow All Projects
cCreate Project
dEdit Project
eDelete/Archive Project
fRestore Project
gClient List Update
cTask Boards
aBoard Preview
bCreate Board
cEdit Board


dDelete/Archive Board
eRestore Board
fAdd/Remove to Members Board
dTask List
aCreate Task List
bEdit Task List
cImport Client
dDelete/Archive List
Notifications
aEmail
bTop Notification Bell Icon Panel
cDevelopers Note:
iModel: Notification
iiView: n\A
iiiController: BoardController
ivMethods: sendNotification, clearNotification


