# SupportDocs: DataSource
This branch is where SupportDocs gets its data! You can add, edit, and delete documents here. For usage instructions, check out the `README`'s [usage](https://github.com/aheze/SupportDocs#using-the-github-repo) section in the main branch.

## Data Source JSON URL
<a href="https://raw.githubusercontent.com/Jwerfel/JSmartWatchDocs/DataSource/_data/supportdocs_datasource.json">https://raw.githubusercontent.com/Jwerfel/JSmartWatchDocs/DataSource/_data/supportdocs_datasource.json</a>

<details>
<summary><strong>Show examples</strong></summary>

<hr>

### SwiftUI
```swift
struct SwiftUIExampleView_MinimalCode: View {
    let dataSource = URL(string: "https://raw.githubusercontent.com/Jwerfel/JSmartWatchDocs/DataSource/_data/supportdocs_datasource.json")!
    @State var supportDocsPresented = false
    
    var body: some View {
        Button("Present SupportDocs from SwiftUI!") { supportDocsPresented = true }
        .sheet(isPresented: $supportDocsPresented, content: {
            SupportDocsView(dataSource: dataSource, isPresented: $supportDocsPresented)
        })
    }
}
```

### UIKit
```swift
class UIKitExampleController_MinimalCode: UIViewController {
    /**
    Connect this inside the storyboard.
    
    This is just for demo purposes, so it's not connected yet.
    */
    @IBAction func presentButtonPressed(_ sender: Any) {
        let dataSource = URL(string: "https://raw.githubusercontent.com/Jwerfel/JSmartWatchDocs/DataSource/_data/supportdocs_datasource.json")!
    
        let supportDocsViewController = SupportDocsViewController(dataSource: dataSource)
        self.present(supportDocsViewController, animated: true, completion: nil)
    }
}
```

<hr>

</details>

## Table of Contents
- [404 Page](https://Jwerfel.github.io/JSmartWatchDocs/404) (SupportDocs Integrated File) ([edit](https://github.com/Jwerfel/JSmartWatchDocs/edit/DataSource/JSmartWatchDocs/404.md))
- [Scenes](https://Jwerfel.github.io/JSmartWatchDocs/Watch/Scenes) (watch) ([edit](https://github.com/Jwerfel/JSmartWatchDocs/edit/DataSource/Watch/Scenes.md))
- [Settings](https://Jwerfel.github.io/JSmartWatchDocs/Watch/Settings) (watch) ([edit](https://github.com/Jwerfel/JSmartWatchDocs/edit/DataSource/Watch/Settings.md))
- [Token Setup](https://Jwerfel.github.io/JSmartWatchDocs/Setup/TokenSetup) (setup) ([edit](https://github.com/Jwerfel/JSmartWatchDocs/edit/DataSource/Setup/TokenSetup.md))
- [Watch App Installation](https://Jwerfel.github.io/JSmartWatchDocs/Setup/WatchAppInstall) (setup) ([edit](https://github.com/Jwerfel/JSmartWatchDocs/edit/DataSource/Setup/WatchAppInstall.md))
- [Watch OS Version](https://Jwerfel.github.io/JSmartWatchDocs/Setup/WatchOSVersion) (setup) ([edit](https://github.com/Jwerfel/JSmartWatchDocs/edit/DataSource/Setup/WatchOSVersion.md))


## Notes
- Your changes make take up to five minutes to deploy. You can track the deployment progress [here](https://github.com/Jwerfel/JSmartWatchDocs/deployments/activity_log?environment=github-pages).
- Do **not** update this file (`README.md`) directly. Your changes will be overriden the next time you push (the GitHub Action will regenerate this file). Instead, update the file in [`_scripts/README.md`](https://github.com/Jwerfel/JSmartWatchDocs/edit/DataSource/_scripts/README.md). 