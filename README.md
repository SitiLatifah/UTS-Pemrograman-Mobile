# UTS-Pemrograman-Web
**Nama	 : Siti Latifah** <br>
**NIM	   : 312010321** <br>
**Kelas	 : TI.20.D2** <br>
**Matkul : Pemrograman Mobile** <br>

## Syntax 
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="517dp"
        android:layout_height="214dp"
        android:layout_marginBottom="518dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.505"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0"
        app:srcCompat="@drawable/gambar1" />

    <ImageView
        android:id="@+id/imageView2"
        android:layout_width="185dp"
        android:layout_height="134dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.497"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@drawable/gambar2" />

    <ImageView
        android:id="@+id/imageView3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="4dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.496"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView2"
        app:srcCompat="@drawable/gambar3" />

    <ImageView
        android:id="@+id/imageView4"
        android:layout_width="127dp"
        android:layout_height="38dp"
        android:layout_marginTop="4dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView3"
        app:srcCompat="@drawable/gambar4" />

    <ImageView
        android:id="@+id/imageView7"
        android:layout_width="74dp"
        android:layout_height="35dp"
        android:layout_marginTop="4dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView"
        app:srcCompat="@drawable/gamba5" />

    <ImageView
        android:id="@+id/imageView8"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="28dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.496"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView7"
        app:srcCompat="@drawable/gambar6" />

    <ImageView
        android:id="@+id/imageView10"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="28dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.496"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView8"
        app:srcCompat="@drawable/gambar6" />

    <ImageView
        android:id="@+id/imageView11"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="28dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.496"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView10"
        app:srcCompat="@drawable/gambar6" />

    <ImageView
        android:id="@+id/imageView12"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="15dp"
        app:layout_constraintEnd_toEndOf="@+id/imageView8"
        app:layout_constraintHorizontal_bias="0.04"
        app:layout_constraintStart_toStartOf="@+id/imageView8"
        app:layout_constraintTop_toTopOf="@+id/imageView8"
        app:srcCompat="@drawable/gambar7" />

    <ImageView
        android:id="@+id/imageView13"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="15dp"
        app:layout_constraintEnd_toEndOf="@+id/imageView10"
        app:layout_constraintHorizontal_bias="0.033"
        app:layout_constraintStart_toStartOf="@+id/imageView10"
        app:layout_constraintTop_toTopOf="@+id/imageView10"
        app:srcCompat="@drawable/gambar8" />

    <ImageView
        android:id="@+id/imageView14"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="15dp"
        app:layout_constraintEnd_toEndOf="@+id/imageView11"
        app:layout_constraintHorizontal_bias="0.037"
        app:layout_constraintStart_toStartOf="@+id/imageView11"
        app:layout_constraintTop_toTopOf="@+id/imageView11"
        app:srcCompat="@drawable/gambar9" />

    <ImageView
        android:id="@+id/imageView5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="144dp"
        android:layout_marginTop="36dp"
        android:src="@drawable/gambar10"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView11" />

    <ImageView
        android:id="@+id/imageView9"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="52dp"
        android:src="@drawable/gambar11"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.482"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView11" />

    <ImageView
        android:id="@+id/imageView15"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:src="@drawable/gambar12"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView5" />
</androidx.constraintlayout.widget.ConstraintLayout>
```
## Output
![Screenshot (156)](https://github.com/SitiLatifah/UTS-Pemrograman-Web/assets/73010098/eadec125-6963-4b4a-9f1b-220fddd3b80d)


