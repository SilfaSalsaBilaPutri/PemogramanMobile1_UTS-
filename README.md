| Nama: | SIlfa Salsa Bila Putri |
| --- | --- |
| NIM: | 312310607 |
| Kelas: | TI.23.A6 |

# 1. Actifity_main.xml

![1](https://github.com/user-attachments/assets/7b298965-3d80-4531-88c5-e971dc2ca570)

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/gambar1"
        android:layout_width="432dp"
        android:layout_height="771dp"
        android:src="@drawable/spals"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="-7dp"
        tools:layout_editor_absoluteY="-7dp" />


</androidx.constraintlayout.widget.ConstraintLayout>
```

# 2. Actifity_login_sign_up.xml

![3](https://github.com/user-attachments/assets/9548ed03-439c-455e-b695-60ac041f6b14)

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".LoginSignUp"
    android:background="@drawable/bb">

    <ImageView
        android:id="@+id/gambar1"
        android:layout_width="62dp"
        android:layout_height="54dp"
        android:src="@drawable/logo"
        app:layout_constraintEnd_toStartOf="@id/gambar2"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginStart="16dp"
        android:layout_marginTop="16dp" />

    <ImageView
        android:id="@+id/gambar2"
        android:layout_width="114dp"
        android:layout_height="26dp"
        android:layout_marginStart="8dp"
        android:layout_marginTop="12dp"
        android:src="@drawable/tixpop"
        app:layout_constraintStart_toEndOf="@id/gambar1"
        app:layout_constraintTop_toTopOf="@id/gambar1" />

    <ImageView
        android:id="@+id/gambar3"
        android:layout_width="287dp"
        android:layout_height="311dp"
        android:layout_marginTop="16dp"
        android:src="@drawable/welcome"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/gambar2" />

    <ImageView
        android:id="@+id/gambar4"
        android:layout_width="419dp"
        android:layout_height="363dp"
        android:layout_marginTop="1dp"
        android:src="@drawable/bingkai_pink"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/gambar3" />

    <TextView
        android:id="@+id/text1"
        android:layout_width="369dp"
        android:layout_height="108dp"
        android:layout_marginTop="30dp"
        android:fontFamily="@font/trocchi_regular"
        android:gravity="center"
        android:text="Nikmati pengalaman menonton tanpa gangguan dengan memesan tiket bioskop favoritmu secara online, bebas antri, dan langsung pilih kursi terbaik!"
        android:textColor="@color/black"
        android:textSize="18dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/gambar3"
        tools:ignore="MissingConstraints" />

    <ImageButton
        android:id="@+id/button1"
        android:layout_width="344dp"
        android:layout_height="60dp"
        android:layout_marginTop="24dp"
        android:background="@drawable/login"
        android:contentDescription="Login Button"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.507"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/text1" />

    <ImageButton
        android:id="@+id/button2"
        android:layout_width="344dp"
        android:layout_height="60dp"
        android:layout_marginTop="24dp"
        android:background="@drawable/signup"
        android:contentDescription="Signup Button"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.507"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/button1" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

# 3. Activity_sign_up.xml

![4](https://github.com/user-attachments/assets/a8caaeed-6b58-4c58-be1c-bc2d2d575001)

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".SignUp"
    android:background="@drawable/bb">

    <TextView
        android:id="@+id/text1"
        android:layout_width="250dp"
        android:layout_height="42dp"
        android:fontFamily="@font/times_new_roman"
        android:text="Create an account"
        android:textColor="@color/black"
        android:textSize="30sp"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="60dp"/>

    <LinearLayout
        android:id="@+id/linear1"
        android:layout_width="328dp"
        android:layout_height="297dp"
        android:layout_marginTop="50dp"
        android:orientation="vertical"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.807"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/text1">

        <EditText
            android:id="@+id/editext1"
            android:layout_width="332dp"
            android:layout_height="61dp"
            android:backgroundTint="@color/PinkMuda"
            android:hint="Enter Your Full Name"
            android:paddingStart="6dp"
            android:textColorHint="@color/PinkMuda" />

        <EditText
            android:id="@+id/edittext2"
            android:layout_width="332dp"
            android:layout_height="61dp"
            android:layout_marginTop="1dp"
            android:backgroundTint="@color/PinkMuda"
            android:hint="Enter Your Email"
            android:paddingStart="6dp"
            android:textColorHint="@color/PinkMuda" />

        <EditText
            android:id="@+id/edittext3"
            android:layout_width="332dp"
            android:layout_height="61dp"
            android:layout_marginTop="1dp"
            android:backgroundTint="@color/PinkMuda"
            android:hint="Create Password"
            android:paddingStart="6dp"
            android:textColorHint="@color/PinkMuda" />

        <EditText
            android:id="@+id/edittext4"
            android:layout_width="332dp"
            android:layout_height="61dp"
            android:layout_marginTop="1dp"
            android:backgroundTint="@color/PinkMuda"
            android:hint="Confirm Password"
            android:paddingStart="6dp"
            android:textColorHint="@color/PinkMuda" />

    </LinearLayout>

    <ImageView
        android:id="@+id/gambar1"
        android:layout_width="34dp"
        android:layout_height="49dp"
        android:layout_marginStart="24dp"
        android:layout_marginTop="4dp"
        android:src="@drawable/icon_orang"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/linear1" />

    <ImageView
        android:id="@+id/gambar2"
        android:layout_width="34dp"
        android:layout_height="49dp"
        android:layout_marginStart="24dp"
        android:layout_marginTop="16dp"
        android:src="@drawable/icon_gmail"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/gambar1" />

    <ImageView
        android:id="@+id/gambar3"
        android:layout_width="34dp"
        android:layout_height="49dp"
        android:layout_marginStart="24dp"
        android:layout_marginTop="16dp"
        android:src="@drawable/icon_password"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/gambar2" />

    <ImageView
        android:id="@+id/gambar4"
        android:layout_width="34dp"
        android:layout_height="49dp"
        android:layout_marginStart="24dp"
        android:layout_marginTop="16dp"
        android:src="@drawable/icon_password"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/gambar3" />

    <ImageButton
        android:id="@+id/gambarb1"
        android:layout_width="344dp"
        android:layout_height="60dp"
        android:background="@drawable/signup"
        android:contentDescription="Signup Button"
        app:layout_constraintTop_toBottomOf="@id/linear1"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="30dp"/>

</androidx.constraintlayout.widget.ConstraintLayout>
```

# 4. Activity_login.xml

![5](https://github.com/user-attachments/assets/782de48a-30d2-4264-a692-7bd93860970a)

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".Login"
    android:background="@drawable/bb">

    <TextView
        android:id="@+id/text1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="@font/times_new_roman"
        android:text="Login"
        android:textColor="@color/black"
        android:textSize="50sp"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="60dp" />

    <LinearLayout
        android:id="@+id/linear1"
        android:layout_width="353dp"
        android:layout_height="154dp"
        android:layout_marginTop="50dp"
        android:orientation="vertical"
        android:paddingHorizontal="16dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.918"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/text1"> <!-- Menambahkan padding horizontal -->

        <EditText
            android:id="@+id/login_email"
            android:layout_width="324dp"
            android:layout_height="67dp"
            android:backgroundTint="@color/PinkMuda"
            android:hint="Enter Your Email"
            android:paddingStart="8dp"
            android:paddingEnd="8dp"
            android:textColorHint="@color/PinkMuda" />

        <EditText
            android:id="@+id/login_password"
            android:layout_width="match_parent"
            android:layout_height="55dp"
            android:layout_marginTop="16dp"
            android:backgroundTint="@color/PinkMuda"
            android:hint="Create Password"
            android:paddingStart="8dp"
            android:paddingEnd="8dp"
            android:textColorHint="@color/PinkMuda" />
    </LinearLayout>

    <ImageView
        android:id="@+id/gambar1"
        android:layout_width="39dp"
        android:layout_height="52dp"
        android:layout_marginStart="16dp"
        android:layout_marginTop="8dp"
        android:src="@drawable/icon_gmail"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@id/linear1" />

    <ImageView
        android:id="@+id/gambar2"
        android:layout_width="39dp"
        android:layout_height="52dp"
        android:layout_marginStart="16dp"
        android:layout_marginTop="15dp"
        android:src="@drawable/icon_password"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/gambar1" />

    <ImageButton
        android:id="@+id/login_button"
        android:layout_width="0dp"
        android:layout_height="60dp"
        android:background="@drawable/login"
        android:contentDescription="Login Button"
        app:layout_constraintTop_toBottomOf="@id/linear1"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="50dp"
        android:layout_marginHorizontal="16dp"/> <!-- Menambahkan margin horizontal -->

</androidx.constraintlayout.widget.ConstraintLayout>
```

# 5. Activity_menu.xml

![6](https://github.com/user-attachments/assets/529d8541-7921-45dc-ba88-6a4dad324106)

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".Menu"
    android:background="@drawable/bb">

    <ImageView
        android:id="@+id/icon1"
        android:layout_width="49dp"
        android:layout_height="53dp"
        android:src="@drawable/icon_orang"
        tools:layout_editor_absoluteX="16dp"
        tools:layout_editor_absoluteY="16dp"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/text1"
        android:layout_width="180dp"
        android:layout_height="60dp"
        android:fontFamily="@font/jacques_francois_shadow"
        android:text="TIXPOP"
        android:textColor="@color/black"
        android:textSize="40dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.497"
        app:layout_constraintStart_toStartOf="parent"
        tools:layout_editor_absoluteY="16dp"
        tools:ignore="MissingConstraints" />

    <ImageView
        android:id="@+id/gambar3"
        android:layout_width="40dp"
        android:layout_height="42dp"
        android:layout_marginStart="48dp"
        android:src="@drawable/bell"
        app:layout_constraintStart_toEndOf="@id/text1"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteY="27dp" />

    <LinearLayout
        android:id="@+id/linear1"
        android:layout_width="392dp"
        android:layout_height="335dp"
        android:orientation="horizontal"
        app:layout_constraintTop_toBottomOf="@+id/text1"
        tools:ignore="MissingConstraints">

        <androidx.cardview.widget.CardView
            android:id="@+id/card1"
            android:layout_width="199dp"
            android:layout_height="335dp"
            android:onClick="onCardViewClick"
            app:cardBackgroundColor="@color/PinkMuda"
            tools:layout_editor_absoluteY="81dp">

            <LinearLayout
                android:layout_width="195dp"
                android:layout_height="329dp"
                android:orientation="vertical">

                <ImageView
                    android:id="@+id/filem1"
                    android:layout_width="177dp"
                    android:layout_height="257dp"
                    android:layout_gravity="center_horizontal"
                    android:layout_marginTop="20dp"
                    android:src="@drawable/bolehkah_sekali" />

                <TextView
                    android:id="@+id/bintang1"
                    android:layout_width="160dp"
                    android:layout_height="33dp"
                    android:layout_gravity="center"
                    android:layout_marginTop="10dp"
                    android:text="⭐⭐⭐⭐"
                    android:textSize="25dp" />
            </LinearLayout>
        </androidx.cardview.widget.CardView>

        <androidx.cardview.widget.CardView
            android:id="@+id/card2"
            android:layout_width="199dp"
            android:layout_height="335dp"
            android:onClick="onCardViewClick"
            app:cardBackgroundColor="@color/PinkMuda">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:orientation="vertical">

                <ImageView
                    android:id="@+id/filem2"
                    android:layout_width="197dp"
                    android:layout_height="255dp"
                    android:layout_marginTop="20dp"
                    android:src="@drawable/perewangan" />

                <TextView
                    android:id="@+id/bintang2"
                    android:layout_width="160dp"
                    android:layout_height="33dp"
                    android:layout_gravity="center"
                    android:layout_marginTop="10dp"
                    android:text="⭐⭐⭐⭐⭐"
                    android:textSize="25dp" />
            </LinearLayout>
        </androidx.cardview.widget.CardView>
    </LinearLayout>

    <LinearLayout
        android:id="@+id/linear2"
        android:layout_width="392dp"
        android:layout_height="335dp"
        android:layout_marginTop="0dp"
        android:orientation="horizontal"
        app:layout_constraintTop_toBottomOf="@id/linear1"
        tools:ignore="MissingConstraints">

        <androidx.cardview.widget.CardView
            android:id="@+id/card3"
            android:layout_width="199dp"
            android:layout_height="335dp"
            android:onClick="onCardViewClick"
            app:cardBackgroundColor="@color/PinkMuda"
            tools:layout_editor_absoluteY="81dp">

            <LinearLayout
                android:layout_width="195dp"
                android:layout_height="329dp"
                android:orientation="vertical">

                <ImageView
                    android:id="@+id/filem3"
                    android:layout_width="wrap_content"
                    android:layout_height="257dp"
                    android:layout_marginTop="20dp"
                    android:src="@drawable/venom" />

                <TextView
                    android:id="@+id/bintang3"
                    android:layout_width="160dp"
                    android:layout_height="33dp"
                    android:layout_gravity="center"
                    android:layout_marginTop="10dp"
                    android:text="⭐⭐⭐⭐⭐"
                    android:textSize="25dp"/>
            </LinearLayout>
        </androidx.cardview.widget.CardView>

        <androidx.cardview.widget.CardView
            android:id="@+id/card4"
            android:layout_width="197dp"
            android:layout_height="match_parent"
            android:onClick="onCardViewClick"
            app:cardBackgroundColor="@color/PinkMuda">

            <ImageView
                android:id="@+id/filem4"
                android:layout_width="195dp"
                android:layout_height="259dp"
                android:layout_marginTop="20dp"
                android:src="@drawable/loan" />

            <TextView
                android:id="@+id/bintang4"
                android:layout_width="160dp"
                android:layout_height="33dp"
                android:layout_gravity="center"
                android:text="⭐⭐⭐⭐"
                android:textSize="25dp"
                android:layout_marginTop="135dp"/>
        </androidx.cardview.widget.CardView>
    </LinearLayout>
    
</androidx.constraintlayout.widget.ConstraintLayout>
```

# 6. Activity_film1.xml

![7](https://github.com/user-attachments/assets/8bfbde0a-8117-4bf0-81c0-419cad4cd2f0)

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".filem1"
    android:background="@drawable/bb">

    <TextView
        android:id="@+id/text1"
        android:layout_width="154dp"
        android:layout_height="36dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="NOW PLAYING"
        android:textColor="@color/black"
        android:textSize="20dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.533"
        app:layout_constraintStart_toStartOf="parent"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteY="33dp" />

    <ImageView
        android:id="@+id/gambar1"
        android:layout_width="723dp"
        android:layout_height="829dp"
        android:layout_marginTop="5dp"
        android:scrollbarSize="30dp"
        android:src="@drawable/bpink"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/text1"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="-156dp" />

    <ImageView
        android:id="@+id/filem1"
        android:layout_width="191dp"
        android:layout_height="221dp"
        android:src="@drawable/bolehkah_sekali"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteY="101dp"
        app:layout_constraintTop_toBottomOf="@id/text1"
        app:layout_constraintEnd_toStartOf="@id/filmName1"
        android:layout_marginTop="35dp"/>

    <TextView
        android:id="@+id/filmName1"
        android:layout_width="193dp"
        android:layout_height="76dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="BOLEHKAH SEKALI SAJA KUMENANGIS"
        android:textColor="@color/black"
        android:textSize="20dp"
        android:layout_marginTop="15dp"
        app:layout_constraintStart_toEndOf="@id/filem1"
        app:layout_constraintTop_toTopOf="@id/filem1"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/text3"
        android:layout_width="136dp"
        android:layout_height="36dp"
        android:text="⭐⭐⭐⭐"
        android:textSize="20dp"
        app:layout_constraintStart_toStartOf="@id/filmName1"
        app:layout_constraintTop_toBottomOf="@id/filmName1"
        android:layout_marginTop="0dp"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/text4"
        android:layout_width="145dp"
        android:layout_height="30dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="Komedi, Horor"
        android:textColor="@color/black"
        android:textSize="16dp"
        app:layout_constraintStart_toStartOf="@id/filmName1"
        app:layout_constraintTop_toBottomOf="@id/text3"
        android:layout_marginTop="0dp"
        tools:ignore="MissingConstraints" />

    <ImageView
        android:id="@+id/gambar2"
        android:layout_width="24dp"
        android:layout_height="34dp"
        android:src="@drawable/timer"
        app:layout_constraintStart_toStartOf="@id/filmName1"
        app:layout_constraintTop_toBottomOf="@id/text4"
        android:layout_marginTop="1dp"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/text5"
        android:layout_width="130dp"
        android:layout_height="25dp"
        android:layout_marginStart="8dp"
        android:layout_marginTop="5dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="1 Jam 41 Menit"
        android:textColor="@color/black"
        android:textSize="16dp"
        app:layout_constraintStart_toEndOf="@id/gambar2"
        app:layout_constraintTop_toTopOf="@id/gambar2"
        tools:ignore="MissingConstraints" />

    <ImageView
        android:id="@+id/gambar3"
        android:layout_width="40dp"
        android:layout_height="42dp"
        android:src="@drawable/bell"
        tools:layout_editor_absoluteX="334dp"
        tools:layout_editor_absoluteY="16dp"
        app:layout_constraintStart_toEndOf="@id/text1"
        android:layout_marginStart="70dp"
        tools:ignore="MissingConstraints" />

    <ImageView
        android:id="@+id/gambar4"
        android:layout_width="75dp"
        android:layout_height="36dp"
        android:layout_marginEnd="320dp"
        android:src="@drawable/baseline_arrow_back_ios_24"
        app:layout_constraintEnd_toEndOf="parent"
        tools:layout_editor_absoluteY="22dp"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/text6"
        android:layout_width="372dp"
        android:layout_height="258dp"
        android:layout_marginTop="35dp"
        android:fontFamily="@font/times_new_roman"
        android:text="Bahasa Indonesia – Setelah kakaknya meninggalkan rumah, Tari berjuang sendirian untuk menyelamatkan Ibunya dari Ayahnya yang abusive. Tari yang sejak kecil menyimpan banyak sekali trauma, sudah tidak mampu menahan beban ini. Ditemani Baskara, seorang pria temperamental yang juga bergabung di support group yang sama. Mampukah Tari melewati Trauma yang ia punya dan tidak lagi menyimpan tangisnya sendiri?"
        android:textColor="@color/black"
        android:textSize="20dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/filem1"
        tools:ignore="MissingConstraints" />

    <ImageButton
        android:id="@+id/buytiket"
        android:layout_width="393dp"
        android:layout_height="62dp"
        android:layout_marginTop="28dp"
        android:background="@drawable/bb_button"
        android:contentDescription="pemesanan"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/text6"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/text7"
        android:layout_width="123dp"
        android:layout_height="34dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="BUY TIKET"
        android:textColor="@color/black"
        android:textSize="20dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="@+id/buytiket"
        tools:layout_editor_absoluteY="652dp"
        app:layout_constraintTop_toBottomOf="@id/text6"
        android:layout_marginTop="40dp"
        tools:ignore="MissingConstraints" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

# 7. Activity_pemesanan.xml

![8](https://github.com/user-attachments/assets/28ff5ef2-8bbe-4a6d-bb92-a257cfb6e846)

![9](https://github.com/user-attachments/assets/1b415977-da3e-44d5-bac7-329706806bb9)

```
<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:fillViewport="true">

    <androidx.constraintlayout.widget.ConstraintLayout
        android:id="@+id/main"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        tools:context=".Pemesanan"
        android:background="@drawable/bb">

        <TextView
            android:id="@+id/title"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="32dp"
            android:fontFamily="@font/times_new_roman"
            android:paddingBottom="10dp"
            android:text="Pembayaran Tiket Bioskop"
            android:textColor="@color/black"
            android:textSize="22sp"
            android:textStyle="bold"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <TextView
            android:id="@+id/location"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginStart="16dp"
            android:text="Lokasi Bioskop :"
            android:textSize="16dp"
            android:textColor="@color/black"
            android:layout_marginTop="10dp"
            android:fontFamily="@font/trocchi_regular"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@id/title" />

        <Spinner
            android:id="@+id/spinnerLocation"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginTop="8dp"
            android:background="@color/PinkMuda"
            android:padding="13dp"
            android:minHeight="48dp"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="1.0"
            android:layout_marginHorizontal="16dp"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@id/location" />

        <TextView
            android:id="@+id/seatTypeLabel"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Pilih Jenis Kursi :"
            android:textSize="16dp"
            android:fontFamily="@font/trocchi_regular"
            app:layout_constraintTop_toBottomOf="@id/spinnerLocation"
            app:layout_constraintStart_toStartOf="parent"
            android:layout_margin="16dp"
            android:textColor="@color/black"/>

        <Spinner
            android:id="@+id/seatTypeSpinner"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:background="@color/PinkMuda"
            android:padding="13dp"
            android:minHeight="48dp"
            app:layout_constraintTop_toBottomOf="@id/seatTypeLabel"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            android:layout_marginHorizontal="16dp" />

        <TextView
            android:id="@+id/pilihTanggal"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Pilih Tanggal :"
            android:textSize="16dp"
            android:textColor="@color/black"
            android:fontFamily="@font/trocchi_regular"
            app:layout_constraintTop_toBottomOf="@id/seatTypeSpinner"
            app:layout_constraintStart_toStartOf="parent"
            android:layout_margin="16dp" />

        <DatePicker
            android:id="@+id/data_pick"
            android:layout_width="348dp"
            android:layout_height="wrap_content"
            android:layout_marginTop="16dp"
            android:calendarViewShown="false"
            android:datePickerMode="calendar"
            android:background="@color/PinkMuda"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@id/pilihTanggal" />

        <TextView
            android:id="@+id/pilihWaktu"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Waktu Yang Di Pilih :"
            android:textSize="16dp"
            android:textColor="@color/black"
            android:fontFamily="@font/trocchi_regular"
            app:layout_constraintTop_toBottomOf="@id/data_pick"
            app:layout_constraintStart_toStartOf="parent"
            android:layout_margin="16dp" />

        <TimePicker
            android:id="@+id/timepick"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="24dp"
            android:background="@color/PinkMuda"
            android:timePickerMode="spinner"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.206"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@id/pilihWaktu"
            tools:ignore="MissingConstraints" />

        <TextView
            android:id="@+id/jenisdipilih"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Jenis yang di pilih :"
            android:textSize="16dp"
            android:textColor="@color/black"
            android:fontFamily="@font/trocchi_regular"
            app:layout_constraintTop_toBottomOf="@id/timepick"
            app:layout_constraintStart_toStartOf="parent"
            android:layout_margin="16dp"
            android:gravity="left" />

        <TextView
            android:id="@+id/harga"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Harga"
            android:textSize="20dp"
            android:textColor="@color/black"
            android:fontFamily="@font/trocchi_regular"
            app:layout_constraintTop_toBottomOf="@id/jenisdipilih"
            app:layout_constraintStart_toStartOf="parent"
            android:layout_margin="16dp"
            android:gravity="left" />

        <TextView
            android:id="@+id/metodePembayaran"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Add Payment Metod :"
            android:textSize="16dp"
            android:textColor="@color/black"
            android:fontFamily="@font/trocchi_regular"
            app:layout_constraintTop_toBottomOf="@id/harga"
            app:layout_constraintStart_toStartOf="parent"
            android:layout_margin="16dp"
            android:gravity="left" />

        <Spinner
            android:id="@+id/bankSpinner"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:background="@color/PinkMuda"
            android:padding="13dp"
            android:minHeight="48dp"
            app:layout_constraintTop_toBottomOf="@id/metodePembayaran"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            android:layout_marginHorizontal="16dp" />

        <TextView
            android:id="@+id/rekening"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Nomer Rekening :"
            android:textSize="16dp"
            android:fontFamily="@font/trocchi_regular"
            android:textColor="@color/black"
            app:layout_constraintTop_toBottomOf="@id/bankSpinner"
            app:layout_constraintStart_toStartOf="parent"
            android:layout_margin="16dp"
            android:gravity="left" />

        <EditText
            android:id="@+id/norek"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_margin="16dp"
            android:layout_marginTop="8dp"
            android:hint="Enter Your Account Number"
            android:textColorHint="@color/PinkMuda"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.005"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@id/rekening"
            tools:ignore="MissingConstraints" />

        <ImageButton
            android:id="@+id/btnPay"
            android:layout_width="393dp"
            android:layout_height="62dp"
            android:layout_marginStart="8dp"
            android:layout_marginTop="28dp"

            android:background="@drawable/bb_button"
            android:contentDescription="Bayar"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@id/norek"
            tools:ignore="MissingConstraints" />

        <TextView
            android:id="@+id/buttonText"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="BUY TIKET"
            android:textColor="@color/black"
            android:textSize="20dp"
            android:layout_marginTop="15dp"
            android:fontFamily="@font/trocchi_regular"
            app:layout_constraintTop_toTopOf="@id/btnPay"
            app:layout_constraintStart_toStartOf="@id/btnPay"
            app:layout_constraintEnd_toEndOf="@id/btnPay"
            android:gravity="center" />

    </androidx.constraintlayout.widget.ConstraintLayout>
</ScrollView>
```

# 8. Activity_tiket_saya.xml

![10](https://github.com/user-attachments/assets/fc06ed09-554f-4f8b-82aa-1861796d7311)

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".TiketSaya"
    android:background="@drawable/bb">

    <TextView
        android:id="@+id/text1"
        android:layout_width="154dp"
        android:layout_height="36dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="TIKET SAYA"
        android:textColor="@color/black"
        android:layout_marginTop="30dp"
        android:textSize="20dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.533"
        app:layout_constraintStart_toStartOf="parent"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteY="33dp"/>

    <ImageView
        android:id="@+id/gambar1"
        android:layout_width="420dp"
        android:layout_height="219dp"
        android:layout_marginTop="15dp"
        android:src="@drawable/vector"

        app:layout_constraintTop_toBottomOf="@id/text1"
        tools:layout_editor_absoluteX="-6dp"
        tools:ignore="MissingConstraints"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"/>

    <TextView
        android:id="@+id/locationText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="@font/trocchi_regular"
        android:textColor="@color/black"
        android:textSize="16dp"
        android:text="Lokasi"
        android:layout_marginTop="45dp"
        app:layout_constraintTop_toBottomOf="@id/text1"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        tools:layout_editor_absoluteY="113dp"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/seatTypeText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_margin="35dp"
        android:layout_marginStart="36dp"
        android:layout_marginTop="80dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="Jenis Kursi"
        android:textColor="@color/black"
        android:textSize="16dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/filmNameText"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/filmNameText"
        android:layout_width="259dp"
        android:layout_height="72dp"
        android:layout_marginStart="60dp"
        android:layout_marginTop="15dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="Nama Filem"
        android:textColor="@color/black"
        android:textSize="20dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/locationText"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/dateText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="212dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="Tanggal"
        android:textColor="@color/black"
        android:textSize="16dp"
        android:layout_marginTop="90dp"
        app:layout_constraintTop_toBottomOf="@id/locationText"
        app:layout_constraintStart_toStartOf="parent"
        tools:layout_editor_absoluteY="226dp"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/timeText"
        android:layout_width="87dp"
        android:layout_height="21dp"
        android:layout_marginStart="212dp"
        android:layout_marginTop="10dp"
        android:fontFamily="@font/trocchi_regular"
        android:text="Waktu"
        android:textColor="@color/black"
        android:textSize="16dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/dateText"
        tools:ignore="MissingConstraints" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
