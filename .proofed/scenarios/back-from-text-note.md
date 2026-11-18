---
name: Return to the notes list from a text note
target: android
execution: local
device: Pixel_8_API_34
os_version: '14'
paths: [app/build.gradle.kts, app/src/main/AndroidManifest.xml, app/src/main/java/org/qosp/notes/App.kt, app/src/main/java/org/qosp/notes/components/backup/BackupService.kt, app/src/main/java/org/qosp/notes/data/AppDatabase.kt, app/src/main/java/org/qosp/notes/data/repo/NoteRepository.kt, app/src/main/java/org/qosp/notes/di/PreferencesModule.kt, app/src/main/java/org/qosp/notes/ui/MainActivity.kt, app/src/main/java/org/qosp/notes/ui/common/AbstractNotesFragment.kt, app/src/main/java/org/qosp/notes/ui/launcher/LauncherActivity.kt, app/src/main/java/org/qosp/notes/ui/launcher/LauncherViewModel.kt, app/src/main/java/org/qosp/notes/ui/main/MainFragment.kt, app/src/main/java/org/qosp/notes/ui/tags/TagsViewModel.kt, app/src/main/java/org/qosp/notes/ui/theme/Color.kt, app/src/main/java/org/qosp/notes/ui/theme/Theme.kt, app/src/main/java/org/qosp/notes/ui/theme/Type.kt, app/src/main/java/org/qosp/notes/ui/utils/ActivityResultUtils.kt, gradle/libs.versions.toml, gradle/wrapper/gradle-wrapper.properties]
---
1. If the welcome screen appears, tap Next to open the notes list. Dismiss any permission prompts.
2. Tap the plus button to open a new text note.
3. Enter Milk as the title and Buy one carton. as the note body.
4. If the on-screen keyboard is visible, dismiss it. With the note editor visible and the keyboard hidden, press Android system Back once.
5. Check that the notes list is visible and contains Milk.
Stop after this check.
