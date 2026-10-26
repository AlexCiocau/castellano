# Calle del Castellano + Hablar

This folder is the AI version of the Spanish practice page. The original single-file version is unchanged.

The AI only works when the page is opened from a web address, so the folder needs to be put online once. GitHub Pages does this for free.

## 1. Put the folder online (GitHub Pages)
1. Create a free account on github.com and click **New repository**. Name it, for example, `castellano`, keep it **Public**, and create it.
2. Click **uploading an existing file** and drag in every file from this folder (unzip it first; upload the files, not the zip). Click **Commit changes**.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and click **Save**.
4. After a minute or two, the page is at `https://YOUR-USERNAME.github.io/castellano/`.

The page is public, but your progress and conversations stay on your device.

## 2. Install it on the iPhone or iPad (on wifi)
1. Open the address in Safari, tap **Share → Add to Home Screen**.
2. Open the app **from the Home Screen icon** (it keeps its own storage, separate from Safari).
3. Go to **Hablar**. The device check should show a green tick. You need iOS / iPadOS 26 or later.
4. Download **Gemma 3 · 1B** first. Then start a conversation.

## 3. Test the flight setup
1. Turn on airplane mode.
2. Close the app completely (swipe it away), then open it again from the icon.
3. Go to **Hablar**, load the model, and have a short conversation.

If the app restarts while loading a model, the device ran out of memory: use a smaller model and close other apps.

`webllm.js` is the WebLLM library (Apache-2.0 licence, see `webllm-LICENSE.txt`).
