# ImageTinier Privacy Policy

Last updated: November 12, 2026

ImageTinier is a local image compression and format conversion app for macOS. This Privacy Policy explains how images, file information, and other data are handled when you use ImageTinier.

## 1. Information We Do Not Collect

ImageTinier does not require registration or sign-in and does not use developer-operated servers. The app does not collect or transmit your images, filenames, file paths, image metadata, usage history, or device identifiers to the developer.

The app contains no advertising, user tracking, or third-party behavioral analytics SDKs. Your images are not used to train AI models.

## 2. Image and File Processing

When you add images using the file picker or drag and drop, ImageTinier reads the file contents and information needed for processing, such as filenames, file sizes, dimensions, formats, and image metadata, on your Mac. This information is used to generate previews, compress images, resize images, and convert formats.

All processing takes place locally. ImageTinier does not upload your images to the developer or third-party servers. The app processes files you explicitly add and saves results to the location you choose.

Generating previews does not modify original files. The app exports results or replaces originals only when you explicitly save, with confirmation required before replacement. Replacing an original cannot be undone within the app, so keep a backup if needed.

## 3. Local Caches and Temporary Files

To support previews and compression, ImageTinier caches some image data in memory and creates compressed results in the system temporary directory. This data is used only for local processing and is not transmitted to the developer.

When you remove items or clear the queue, the app releases the associated caches and attempts to delete the corresponding temporary results. It also attempts to clean up its temporary directory when its processing service is released. Unexpected termination may leave temporary files behind; subsequent cleanup depends on the operating system's temporary file management.

Removing items or clearing the queue does not delete your original images or exported files. Saved files remain in your chosen location until you manage or delete them yourself.

## 4. Image Metadata

Images may contain metadata such as capture dates, camera information, GPS location, and text comments. ImageTinier may retain some metadata in processed files, depending on the format, processing options, and system encoding support.

Newly encoded WebP output does not retain original EXIF, XMP, or other source metadata. However, when same-format processing does not reduce file size, the app may keep the exact original file bytes, including existing metadata. ImageTinier is not a dedicated metadata removal tool and does not guarantee that every output is free of location data or other sensitive information.

Review output metadata before sharing images if this matters to you.

## 5. File Access Permissions

ImageTinier uses macOS App Sandbox and accesses your selected images or export folders through the system file picker, drag and drop, and system authorization mechanisms. Access is used to read images and save results, not to scan or collect unrelated files.

## 6. Third-Party Components and Apple Services

ImageTinier uses Apple's system image frameworks and bundled local encoding components, including MozJPEG and libwebp. These components process images on your device and are not used as image upload or analytics services. Their open-source notices are available through the app's Open Source Licenses menu item.

If you obtain ImageTinier through the Mac App Store, Apple handles purchases, payments, and related platform data under its own privacy policy and service terms. ImageTinier does not receive your payment card details.

## 7. Data Sharing and Your Control

We do not sell, rent, or share your images or personal information with advertisers.

Because the developer does not receive or store images processed through the app, there are no developer-held server copies to access, export, or delete. You can stop using the app, clear the processing queue, and manage or delete local original and exported files at any time.

If your source files or export location are managed by iCloud Drive or another cloud storage service, that service may sync files according to your settings. Such syncing is handled by the relevant service provider.

## 8. Children's Privacy

ImageTinier does not ask users to provide their age or create an account, and it does not knowingly collect children's personal information through the app.

## 9. Changes to This Policy

If the app's features or data handling practices change, we will update this Privacy Policy and revise the date at the top of this page.

## 10. Contact Us

If you have questions about this Privacy Policy or how ImageTinier handles data, contact:

- Email: [bigtotorouk@gmail.com](mailto:bigtotorouk@gmail.com)
