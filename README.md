Magento 2 Russian Language Package

Installation

*** Step 1: Install a Language Pack ***

composer require atopt/m2-language-ru_ru:*

*** Step 2: Create a Store View for the Language ***

1.	On the Admin sidebar, tap Stores. Then under Settings, choose All Stores.

2.	Tap Create Store View. Then, do the following:
  a.	Choose the Store that is the parent of the view.
  b.	Enter a Name for the store view. For example: Portuguese.
      In the header of the store, the name appears in the “language chooser.”

  c.	Enter a Code in lowercase characters to identify the view. For example: portuguese.
  d.	To activate the view, set Status to “Enabled.”
  e.	(Optional) Enter a Sort Order number to determine the sequence in which this view is                 listed with other views.

3.	When complete, tap Save Store View.

*** Step 3: Change the Locale of the Store View ***
  1.	On the Admin sidebar, tap Stores. Then under Settings, choose Configuration.

  2.	In the upper-left corner, set Store View to the specific view where the configuration  is to apply. When prompted to confirm scope switching, tap OK.

  3.	Expand  the Locale Options section.

  4.	Clear the Use Website checkbox after the Locale field. Then, set Locale to the language that you want to assign to the view.
  If there are several variations of the language available, make sure to choose the one for the specific region or dialect.

  5.	When complete, tap Save Config.
