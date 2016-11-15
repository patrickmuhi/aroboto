# aroboto (Android Roboto TextView)
Clean Roboto Font TextViews, gone are the days where we used the default fonts.


##Usage
1. Download the fonts zip and copy all the fonts into `assets/fonts`

2. Update your `attr.xml` with these:

        <declare-styleable name="RobotoTextView">
                <attr name="typeface" format="enum">
                    <enum name="robotoBlack" value="0" />
                    <enum name="robotoBlackItalic" value="1" />
                    <enum name="robotoBold" value="2" />
                    <enum name="robotoBoldItalic" value="3" />
                    <enum name="robotoBoldCondensed" value="4" />
                    <enum name="robotoBoldCondensedItalic" value="5" />
                    <enum name="robotoCondensed" value="6" />
                    <enum name="robotoCondensedItalic" value="7" />
                    <enum name="robotoItalic" value="8" />
                    <enum name="robotoLight" value="9" />
                    <enum name="robotoLightItalic" value="10" />
                    <enum name="robotoMedium" value="11" />
                    <enum name="robotoMediumItalic" value="12" />
                    <enum name="robotoRegular" value="13" />
                    <enum name="robotoThin" value="14" />
                    <enum name="robotoThinItalic" value="15" />
                </attr>
            </declare-styleable>


3. Start using it!

                <.RobotoTextView
                android:id="@+id/dialog_universal_warning_text"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:maxLines="7"
                android:text="@string/lorem_ipsum_short"
                android:textColor="@color/main_color_grey_600"
                android:textSize="20sp"
                app:typeface="robotoRegular" />
