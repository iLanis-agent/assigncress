# Assigncress 1.0 TEST
Native Android minimum-sum balanced assignment puzzle. Android8+ min26/target35. Package com.gg007.assigncress.

## Rules
Assign six workers A-F to six jobs 1-6. Each table entry is an abstract work-unit cost for that worker-job pair, not money. Choose exactly one cell in every row and use every job column exactly once. Minimize the sum of the six chosen costs. Tap a cost cell to select it, another in the same row to replace it, or the same cell again to clear it. Temporary repeated job columns are allowed while editing, but CHECK rejects them. No hidden automatic reassignment. Finish all six workers and CHECK ASSIGNMENT explicitly. Twelve original 6 x 6 cost tables, one optimum each. Undo/reset and saved palette/optional row letters. This is balanced minimum-sum assignment, not preference stability or a real workforce decision.

## Download and status
https://mega.co.nz/#!4ZNwXC6T!PdDDeYoetKlOGStdtHn4MksW27dNd-caYtqGNT7p35U
APK20974bytes; SHA2566ca2ecc362e7ea6c655be652014f7ce87a446d7639cd1ca16c06c6a5623be8a8. Original certificate SHA2561651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions. GG007 icon unchanged. Anonymous downloaded bytes exact.

## Checks
Independent full-permutation enumeration checks all 720 valid assignments per board,8640 total, against production subset dynamic programming. All 46656 complete row choices per board,559872 total, verify duplicate-column rejection, total costs and optimality. Another 1000 random cost tables,432 choose-undo-clear cases, incomplete/bounds cases and an all-one-cost table with 720 tied optima pass. Twelve actual drawing-adapter cell-choice/CHECK tap-solves, early check, duplicate rejection, clear/undo/reset, solved locks, NEXT, levels/menu/privacy and saved palette/row letters pass. Twenty drawing previews visually inspected, not phone screenshots. Original signing certificate/icon unchanged, no permissions. Anonymous APK bytes match. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Current 239 studio descriptions and 803 legacy descriptions reviewed. Accordcress pairs four people using two-sided rank preferences and forbids blocking pairs; Assigncress pairs six workers and jobs using a cardinal 6 x 6 cost matrix and minimizes the sum. No preferences or stability rule. Slotcress selects non-overlapping time intervals to maximize reward; Covercress chooses possibly overlapping bundles to cover requirements. Here every row and every column is used exactly once. Registry assignment hits were awk field assignment and work-rate arithmetic, not one-to-one minimum-cost matching. No matching factory mechanic found. Known balanced assignment problem adaptation, not a globally new algorithm. Original seeded cost tables, native implementation and assignment-table drawing.

## Build and tests
JDK17/AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/assign-test src/com/gg007/assigncress/Board.java BoardTest.java then java -cp /tmp/assign-test com.gg007.assigncress.BoardTest. bash build.sh produces an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private signing material. No signing secret included. adapter/android is the Java2D drawing adapter used with AssignAdapterTest.java, not an Android runtime.

## Privacy and branding
Assigncress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, row-letter labels and solved-level marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon, studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK/exact cumulative240cardstudio/publishing fragments privately preserved:
https://files.instinct.com/5mhqu6xjv2uv-assigncress-source-archive
https://github.com/iLanis-agent/assigncress holds README only; full Git source pending. All four studio includes and Pages settings unchanged. Both sites verified separately.

## Rule sources
https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.linear_sum_assignment.html
https://developers.google.com/optimization/assignment/linear_assignment
https://developers.google.com/optimization/assignment/assignment_example
https://karthik.ise.illinois.edu/courses/ie511/lectures-sp-25/lecture-1.pdf
https://www.cs.princeton.edu/courses/archive/spr05/cos423/lectures/07assignment.pdf
https://archive.nptel.ac.in/content/storage2/courses/111102012/module9/lect5.pdf
https://en.wikipedia.org/wiki/Assignment_problem
