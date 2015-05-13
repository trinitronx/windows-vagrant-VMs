Windows Vagrant VMs
===================

[Windows Boxes for Vagrant Courtesy of Modern.ie](http://blog.syntaxc4.net/post/2014/09/03/windows-boxes-for-vagrant-courtesy-of-modern-ie.aspx)

Microsoft has introduced, modern.IE, a new way for developers to test Websites for compatibility with Internet Explorer. Modern.IE is a free set of tools and resources designed to make it easier for developers to ensure their sites work beautifully across Internet Explorer as well as other modern browsers. Ryan Gavin, general manager of Internet Explorer at Microsoft, said in a blog post. "As part of the modern.IE release, we're excited to announce a special partnership with BrowserStack, a leading browser testing service that lets developers test their site on any browser on any Windows OS. For any Web developer that visits BrowserStack via modern.IE, we're offering three months of this service for free over the next year," Gavin said. Modern.IE features a wizard that scans for common coding practices that might prevent users from having their best experience on a site. Developers start by entering a Web page URL that they want to test and modern.IE returns a report on the compatibility issues. In honor of the release of the modern.IE, here are a few reasons developers should check out IE again.

How to Use
==========

These Vagrant boxes are simple to use.  Simply change directory into the folder for the version of windows Vagrant box you want to use and run: `vagrant up`.

To share files into the VM, place them in `data/`.

VMs EXPIRE AFTER 90 DAYS!
When you first install the VM, set a snapshot you can roll back to later.

License
=======

The Microsoft Software License Terms for the IE VMs are included in the [release notes][1] and supersede any conflicting Windows license terms included in the VMs. By downloading and using this software, you agree to these [license terms][1].

[1]: http://modernievirt.blob.core.windows.net/vhd/release_notes_license_terms_1_5_15.pdf

Disclaimer
==========

I am not the maintainer of these VMs.  Do NOT file issues if you have problems with the Vagrant boxes themselves.  These are maintaned by [Modern.ie](http://dev.modern.ie/tools/vms/).
