# Project Reunion

Over the last couple of years, we have been breaking down the barriers between Win32 and UWP. We are expanding our efforts even further and finally giving this effort a name: Project Reunion

Project Reunion is:

- **The next evolution of the journey we started with UWP**. It embraces all the goodness and investments our community has done in UWP and Win32, and builds a path forward for both

- **it clears up the confusion around the Windows platform**, and acknowledges that supporting all Windows versions (over 1Billion endpoints),  not just the latest version, and provides meaningful TAM and lowers cost for our developer base

- **This evolution will converge our divergent paths of the past and brings our developer base forward**. It unblocks future scenarios and jumpstarts the revolution of Windows apps (e.g. Cloud streamed, Cloud-hybrid, Cloud/Edge Apps)


### Current App Model
![Appmodel](docs/currentappmodel.PNG)

### Unified App Model(Project Reunion)
![Reunion](docs/newappmodel.PNG)

###  Benefits of Project Reunion

 _Windows and Project Reunion loves all your apps_

The Project Reunion Framework helps you use modern features of Windows across all your apps, across all your
users. You'll get access to modern features of the Windows Application Platform at your own pace.
Improve power use and uphold privacy requirements in your existing apps.  Update your app to use
APIs that automatically switch to fill-in support on older versions of Windows.  Get access to
more of Windows from your UWPs. Connect to notifications from your Win32 applications.


- Your **existing UWP and Win32 apps still work** on supported versions of Windows with **no changes**
- If you build fully against Project Reunion, **we will do the work** to make your app always work across all of Windows. Project Reunion APIs are backwards-compatible across a range of Windows versions and provide a clear
message to you that an API might not be supported.
- You can **incrementally adopt** Project Reunion components for your existing apps and middleware libraries. Project Reunion helps you incrementally adopt powerful Windows features like AppContainer, Desktop
Bridge, Identity, and more
- Project Reunion will **update independent of Windows releases**, and will always have the latest and greatest support for new hardware. Project Reunion stays up to date automatically as new versions are available without recompilation or
updates to your app.
- Project Reunion is an inclusive set of technologies allowing developers **a broad range of choice**.  We will recommend technologies 
that deliver the best experience on the broad set of hardware we support, have great fundamentals, and are optimized for the cloud.
- Project Reunion works for packaged, unpackaged, UWP, Desktop Bridge, and bring-your-own identity apps.
**Write your app or framework code once and use it everywhere**.



### Project Reunion Principles

**Compatible**<br>
	Unifies Win32 and UWP. With project Reunion, you won't have to pick between UWP or Win32<br>
	It works on all supported Windows versions<br>
**Modern**<br>
	It supports the latest libraries for e.g. UI, AI, ML<br>
	Project Reunion helps you get ready for cloud integration, app streaming, edge compute, etc<br>
**Agile**<br>
	Project Reunion ships out of band with OS releases, with regular previews<br>
	You can incrementally adopt Project Reunion components for your existing apps and middleware libraries<br>
**Open**<br>
	We're committing to engineering Project Reunion in the open on GitHub so you have a more direct say in how the platform evolves<br>

## Documentation

* [High level overview](docs/overview.md) - Why we're doing this? how does it benefit you?
* [Roadmap](docs/roadmap.md) - where we're going. We're following a [roadmap](docs/roadmap.md) that gets us to building a v1.0 of Project Reunion exploring
some basic common features.  You can help by filing issues for features you'd like to see!
* [Contributor/developer guide](docs/contributor-guide.md) - How to contribute to Project Reunion.
* [FAQ](docs/faq.md) - frequently asked questions about Project Reunion.


## Version Support

At this time, Project Reunion supports Windows `TargetPlatformVersion` >= 10.0.18362 (Windows 10 1809) or
greater. 

Your app's users can be on any of the following supported Windows 10 versions:

* Windows Insider Previews
* May 2019 Update (18362 aka "19H1")
* October 2018 Update (17763 aka "Redstone 5")
* April 2018 Update (17134 aka "Redstone 4")
* Fall Creators Update (16299 aka "Redstone 3")

When features have partial implementations on older versions of Windows they will have an
[`IsSupported`](docs/developer-guide.md) method indicating what level of support is present.


## Have Your Say!

File a [new issue!](https://github.com/microsoft/ProjectReunion/issues/new/choose) Tell us what problem you're
trying to solve, how you've tried to solve it so far, and what would be the ideal solution for your app.  Bonus
points if there's a gist or existing repo we can look at with you.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
