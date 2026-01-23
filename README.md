# QCTools

___Quality Control Tools for Video Preservation___

QCTools is a software tool that helps users analyze and understand their digitized video files 
through use of audiovisual analytics and filtering to help users detect corruptions or compromises 
	in the results of analog video digitization or in born-digital video.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub net.mediaarea.QCTools
flatpak run net.mediaarea.QCTools
```

## Building

```bash
git clone git@github.com:flathub/net.mediaarea.QCTools.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install net.mediaarea.QCTools.json
```
