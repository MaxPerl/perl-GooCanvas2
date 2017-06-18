# perl-GooCanvas2
Perl binding for GooCanvas2 widget using Glib::Object::Introspection

GooCanvas2 is a new canvas widget for use with Gtk3 that uses the Cairo 2d library for drawing. This is a simple and basic implementation of this wonderful Canvas widget.

# INSTALLATION

To install this module type the following:

   perl Makefile.PL
   make
   make test
   make install

# DEPENDENCIES

This module requires these other modules and libraries:

  Gtk3
  
  Furthermore you need to install the typelib file for GooCanvas-2.0
  on Debian try: "sudo apt-get install gir1.2-goocanvas-2.0"
  on Mageia "urpmi lib64goocanvas-gir2.0" should work

# COPYRIGHT AND LICENCE

Copyright (C) 2017 by Maximilian Lika

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself, either Perl version 5.22.3 or,
at your option, any later version of Perl 5 you may have available.
