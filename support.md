# ImageTinier Support

Need help with ImageTinier? Find answers to common questions below, or contact us at [bigtotorouk@gmail.com](mailto:bigtotorouk@gmail.com).

## Getting Started

1. Add images using the file picker or drag and drop them into the app.
2. Choose an output format, quality, and image size. Previews refresh automatically when you change settings.
3. Select an image to compare the original and compressed previews.
4. Choose **Export to folder** to save separate copies, or **Replace originals** to update the source files after confirmation.

Previewing does not modify your original images. Replacement cannot be undone within ImageTinier, so keep backups when needed. Changing the file format requires exporting to a folder.

## Frequently Asked Questions

### Which image formats are supported?

ImageTinier supports single-image JPEG, PNG, HEIC, and WebP files. Animated images, multipage files, symbolic links, and images larger than 80 megapixels are not supported. WebP output is limited to 16,383 pixels per dimension.

### Are my images uploaded?

No. Image compression and conversion take place locally on your Mac. No account or internet connection is required for image processing. If you use files in a cloud-managed folder, the cloud storage service may sync them according to your settings.

Read our [Privacy Policy](privacy-policy.md) for more information.

### Why does an image show “No Reduction — Original Kept”?

Some images are already efficiently compressed. If processing in the same format does not produce a smaller file, ImageTinier keeps the exact original instead of creating a larger result. This can also happen when resizing. Try a lower quality setting or a different output format if appropriate, and compare the preview before saving. Format conversion can produce a larger file.

### What is the difference between PNG Smart and Lossless modes?

Smart mode reduces the number of colors to help produce smaller files and may slightly change the image's appearance. Lossless mode optimizes compression without changing pixel values when the original dimensions are retained. Resizing or converting an image is a separate operation and may change its pixels.

### What does WebP Lossless mean?

WebP Lossless preserves pixels at the encoding stage after the image has been normalized to 8-bit sRGB and any selected resizing has been applied. It does not guarantee preservation of the source image's original color profile, bit depth, or metadata.

### Why can't I convert a transparent image to JPEG?

JPEG does not support transparency. ImageTinier rejects this conversion to avoid silently removing the transparent background. Choose PNG or WebP to retain transparency.

### Why can't I save yet?

Wait for the latest compression preview to finish. Changing settings starts a new preview, and saving becomes available once the new result is ready. Check the queue for any file-specific error messages.

### What should I do if importing or saving fails?

- Confirm that the image is a supported, valid, single-image file.
- If the file is stored in a cloud folder, make sure it is downloaded and locally available.
- Check that the destination is writable and has enough free space.
- If the original changed after the preview was prepared, remove it from the queue and add it again before retrying.
- Try exporting to a different folder to help identify a destination access issue.

### Will exporting overwrite existing files?

Folder export creates names with a `-compressed` suffix and adds a number when needed to avoid overwriting existing files. Replacing originals is a separate save option that requires confirmation.

### Does removing an image from the queue delete it?

No. Removing an item or clearing the queue only removes its processing state and associated temporary results. Your original images and previously exported files remain in place.

### Does compression remove location or camera metadata?

Some output formats and processing options retain metadata, which may include GPS location and camera information. Newly encoded WebP files omit source metadata, but an original-kept result retains the original file and its metadata. Check output files before sharing if metadata privacy matters to you.

### Can I use ImageTinier to archive RAW, HDR, or Live Photos?

ImageTinier is designed for supported static images. It is not an archival preservation tool for RAW, HDR, Live Photos, or auxiliary image data. Keep the original files when those properties matter.

## Report a Problem

Email [bigtotorouk@gmail.com](mailto:bigtotorouk@gmail.com) with the subject **ImageTinier Support** and include:

- Your ImageTinier version and macOS version.
- A short description of the problem and the steps to reproduce it.
- The input image format and approximate dimensions.
- Your selected output format, quality, resize setting, and save mode.
- Any error message, or a screenshot with personal information removed.

Please do not send private photos, passwords, payment details, or other sensitive information. If a sample image would help, use a non-sensitive test image that reproduces the issue and remove identifying metadata before sending it.

## Feedback and Feature Requests

Have an idea for improving ImageTinier? Send it to [bigtotorouk@gmail.com](mailto:bigtotorouk@gmail.com). Describe what you want to accomplish and how the change would help your workflow.
