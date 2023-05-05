1.  [Back-end Development Handbook](index.html)
2.  [Back-end Development
    Handbook](Back-end-Development-Handbook_262349.html)
3.  [MEETING NOTE](MEETING-NOTE_25198629.html)
4.  [01. Weekly Review](01.-Weekly-Review_27066369.html)
5.  [Q2-2022](Q2-2022_26869761.html)

# Back-end Development Handbook : 2022-08-03.Department-Weekly-Review

Created by Thao Tran, last modified on Aug 03, 2022

  ------------------ -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Date**           03-08-2022
  **Time**           10h5-11h00
  **Participants**   [Thao Tran](https://gotecq-vn.atlassian.net/wiki/people/627e391219b12900682ac0fc?ref=confluence) [Hung Le](https://gotecq-vn.atlassian.net/wiki/people/6000fd1e64208901415ca478?ref=confluence)
  **Location**       4th floor
  **Meeting type**   GG Meeting
  ------------------ -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ![(blue star)](images/icons/emoticons/72/1f4bc.png) Objectives

-   [![](https://gotecq-vn.atlassian.net/images/icons/issuetypes/epic.svg)TPF-1756](https://gotecq-vn.atlassian.net/browse/TPF-1756) -
    CDM + PRC \> Contract Management v1.3.0 Completed

-   [![](https://gotecq-vn.atlassian.net/images/icons/issuetypes/epic.svg)TPF-1921](https://gotecq-vn.atlassian.net/browse/TPF-1921) -
    DAS \> PCP Dashboard v1.1.0 Completed

-   [![](https://gotecq-vn.atlassian.net/images/icons/issuetypes/epic.svg)TPF-1450](https://gotecq-vn.atlassian.net/browse/TPF-1450) -
    EHR \> Encounter Management v1.2.0 Completed

## ![(blue star)](images/icons/emoticons/72/1f31f.png) Important topics

+---+-----------------------------+-------------------------------+
|   | **Topic**                   | **Discussion**                |
+---+-----------------------------+-------------------------------+
| 1 | Clear solution requirements | **1. Contract management**    |
|   |                             |                               |
|   |                             | -   [![](https://gotecq-vn.at |
|   |                             | lassian.net/rest/api/2/univer |
|   |                             | sal_avatar/view/type/issuetyp |
|   |                             | e/avatar/10310?size=medium)TP |
|   |                             | F-1099](https://gotecq-vn.atl |
|   |                             | assian.net/browse/TPF-1099) - |
|   |                             |     Do not show dismissed     |
|   |                             |     documents in element      |
|   |                             |     group preview when        |
|   |                             |     contract package status   |
|   |                             |     is submitted/ completed   |
|   |                             |     Completed                 |
|   |                             |                               |
|   |                             |     -   When package is       |
|   |                             |         **approved** by       |
|   |                             |         network, status of    |
|   |                             |         dismissed element     |
|   |                             |         group is              |
|   |                             |         **completed**. Should |
|   |                             |         we keep this status   |
|   |                             |         as **DISMISSED**      |
|   |                             |         instead of            |
|   |                             |         **COMPLETED** ?       |
|   |                             |                               |
|   |                             |     -   Keep status is        |
|   |                             |         dismised              |
|   |                             |                               |
|   |                             | -   [![](https://gotecq-vn.at |
|   |                             | lassian.net/rest/api/2/univer |
|   |                             | sal_avatar/view/type/issuetyp |
|   |                             | e/avatar/10310?size=medium)TP |
|   |                             | F-1032](https://gotecq-vn.atl |
|   |                             | assian.net/browse/TPF-1032) - |
|   |                             |     \[C\] Do not remove       |
|   |                             |     existing signatures if a  |
|   |                             |     review is declined        |
|   |                             |     Completed                 |
|   |                             |                               |
|   |                             |     -   When operator         |
|   |                             |         declines package,     |
|   |                             |         element group status  |
|   |                             |         is **DECLINED,**      |
|   |                             |         status step is        |
|   |                             |         **ERROR**             |
|   |                             |                               |
|   |                             |     -   How do we show the    |
|   |                             |         status/declined       |
|   |                             |         reason of network     |
|   |                             |         while keeping         |
|   |                             |         provider's sign       |
|   |                             |         request?              |
|   |                             |                               |
|   |                             |     -   Should we keep status |
|   |                             |         of element group as   |
|   |                             |         **SIGNED** ?          |
|   |                             |                               |
|   |                             |     -   Vẫn giữ status SIGNED |
|   |                             |         → change status của   |
|   |                             |         package thành         |
|   |                             |         ubsubmitted           |
|   |                             |                               |
|   |                             | **2. Contact center**         |
|   |                             |                               |
|   |                             | -   Update                    |
|   |                             |     p                         |
|   |                             | ractitioner/organization/work |
|   |                             |     item APIs                 |
|   |                             |                               |
|   |                             | -                             |
|   |                             |  [https://www.figma.com/file/ |
|   |                             | pfjCJa7KGLTVd23OcBWxtP/GoTECQ |
|   |                             | -Contact-Center-rev3.0?node-i |
|   |                             | d=5957%3A63821](https://www.f |
|   |                             | igma.com/file/pfjCJa7KGLTVd23 |
|   |                             | OcBWxtP/GoTECQ-Contact-Center |
|   |                             | -rev3.0?node-id=5957%3A63821) |
|   |                             |                               |
|   |                             | -   Create view in contact    |
|   |                             |                               |
|   |                             | **3. Claim management**       |
|   |                             |                               |
|   |                             | -   Missing data, need data   |
|   |                             |     for data model            |
|   |                             |                               |
|   |                             | -   [https://www.             |
|   |                             | figma.com/file/HNhHz56t3ao9WK |
|   |                             | fI52H3q6/GoTECQ-Encounter-Man |
|   |                             | agement-rev2.2?node-id=9474%3 |
|   |                             | A251819](https://www.figma.co |
|   |                             | m/file/HNhHz56t3ao9WKfI52H3q6 |
|   |                             | /GoTECQ-Encounter-Management- |
|   |                             | rev2.2?node-id=9474%3A251819) |
|   |                             |                               |
|   |                             | **4. PCP dashboard**          |
|   |                             |                               |
|   |                             | -   [![](https://gotecq-vn.at |
|   |                             | lassian.net/rest/api/2/univer |
|   |                             | sal_avatar/view/type/issuetyp |
|   |                             | e/avatar/10315?size=medium)TP |
|   |                             | F-1924](https://gotecq-vn.atl |
|   |                             | assian.net/browse/TPF-1924) - |
|   |                             |     Comment on Dashboard      |
|   |                             |     Completed                 |
|   |                             |                               |
|   |                             | -   [![](https://gotecq-vn.at |
|   |                             | lassian.net/rest/api/2/univer |
|   |                             | sal_avatar/view/type/issuetyp |
|   |                             | e/avatar/10315?size=medium)TP |
|   |                             | F-1928](https://gotecq-vn.atl |
|   |                             | assian.net/browse/TPF-1928) - |
|   |                             |     Starred dashboards        |
|   |                             |     Completed                 |
|   |                             |                               |
|   |                             | -   [![](https://gotecq-vn.at |
|   |                             | lassian.net/rest/api/2/univer |
|   |                             | sal_avatar/view/type/issuetyp |
|   |                             | e/avatar/10315?size=medium)TP |
|   |                             | F-1926](https://gotecq-vn.atl |
|   |                             | assian.net/browse/TPF-1926) - |
|   |                             |     Show work-item list       |
|   |                             |     Completed                 |
|   |                             |                               |
|   |                             | -   Create table to store     |
|   |                             |     dashboard,                |
|   |                             |     **code-display, hoặc      |
|   |                             |     dashboard có              |
|   |                             |     internal_id**             |
|   |                             |                               |
|   |                             | **5. Member company**         |
|   |                             |                               |
|   |                             | -   Member company type là    |
|   |                             |     Other                     |
|   |                             |                               |
|   |                             | -   Auto generate company cho |
|   |                             |     member -\>                |
|   |                             |     create-standalone-user    |
|   |                             |                               |
|   |                             | **6. Convert click here to    |
|   |                             | button**                      |
|   |                             |                               |
|   |                             | -   [TPF-2116](http           |
|   |                             | s://gotecq-vn.atlassian.net/b |
|   |                             | rowse/TPF-2116?src=confmacro) |
|   |                             |                               |
|   |                             | -   Primary action            |
+---+-----------------------------+-------------------------------+
| 2 | Department issues           | **1. Dynamic configuration**  |
|   |                             |                               |
|   |                             | -   Back-End configuration    |
|   |                             |                               |
|   |                             | -   Reload config → Down      |
|   |                             |     server 1 khoảng thời gian |
|   |                             |                               |
|   |                             | -   Signal protocol           |
+---+-----------------------------+-------------------------------+
| 3 |                             |                               |
+---+-----------------------------+-------------------------------+

## ![(blue star)](images/icons/emoticons/72/2705.png) Action items

-    

Document generated by Confluence on May 04, 2023 09:15

[Atlassian](http://www.atlassian.com/)
