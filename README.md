# Pilof
A BottomSheetBehavior framework mirroring Google Maps

## Usage

```xml
<android.support.v4.widget.NestedScrollView
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:id="@+id/bottom_sheet"
            android:background="@android:color/white"
            android:layout_gravity="bottom"
            app:behavior_hideable="true"
            app:behavior_peekHeight="100dp"
            app:behavior_anchorOffset="200dp"
            app:behavior_header_layout="@layout/custom_header"
            app:behavior_content_layout="@layout/custom_content"
            app:behavior_parallax_layout="@layout/parallax"
            app:behavior_anchorColor="@color/colorPrimary"
            app:behavior_collapsedColor="@android:color/white"
            app:layout_behavior="xyz.projectplay.pilof.SheetBehavior">
            ...
</android.support.v4.widget.NestedScrollView>
