# activity_main.xml:

  ```
    <?xml version="1.0" encoding="utf-8"?>
    <androidx.constraintlayout.widget.ConstraintLayout
        xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        xmlns:tools="http://schemas.android.com/tools"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="#000"
        tools:context=".MainActivity">
    
        <Button
            android:id="@+id/button1"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="1"
            android:textColor="@color/black"
            android:textSize="28sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.043"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.817" />
    
        <Button
            android:id="@+id/button2"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="2"
            android:textColor="@color/black"
            android:textSize="28sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.352"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.817" />
    
        <Button
            android:id="@+id/button3"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="3"
            android:textColor="@color/black"
            android:textSize="28sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.672"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.817" />
    
        <Button
            android:id="@+id/button4"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="4"
            android:textColor="@color/black"
            android:textSize="28sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.043"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.677" />
    
        <Button
            android:id="@+id/button5"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="5"
            android:textColor="@color/black"
            android:textSize="28sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.352"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.677" />
    
        <Button
            android:id="@+id/button6"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="6"
            android:textColor="@color/black"
            android:textSize="28sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.672"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.677" />
    
        <Button
            android:id="@+id/button7"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="7"
            android:textColor="@color/black"
            android:textSize="28sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.043"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.541" />
    
        <Button
            android:id="@+id/button8"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="8"
            android:textColor="@color/black"
            android:textSize="28sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.352"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.541" />
    
        <Button
            android:id="@+id/button9"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="9"
            android:textColor="@color/black"
            android:textSize="28sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.672"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.541" />
    
        <Button
            android:id="@+id/button0"
            android:layout_width="185dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="0"
            android:textAlignment="center"
            android:textColor="@color/black"
            android:textSize="40dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.061"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.957" />
    
        <Button
            android:id="@+id/button_equal"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/watermelon"
            android:text="="
            android:textColor="@color/black"
            android:textSize="30dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.99"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.958" />
    
        <Button
            android:id="@+id/button_multi"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/watermelon"
            android:text="×"
            android:textColor="@color/black"
            android:textSize="30dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.99"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.541" />
    
        <Button
            android:id="@+id/button_divide"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/watermelon"
            android:text="/"
            android:textColor="@color/black"
            android:textSize="30dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.987"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.406" />
    
        <Button
            android:id="@+id/button_add"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/watermelon"
            android:text="+"
            android:textColor="@color/black"
            android:textSize="30dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.99"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.817" />
    
        <Button
            android:id="@+id/button_sub"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/watermelon"
            android:text="-"
            android:textColor="@color/black"
            android:textSize="30dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.99"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.677" />
    
        <Button
            android:id="@+id/button_clear"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:text="C"
            android:shape = "oval"
            android:backgroundTint="@color/clear"
            android:textColor="#060606"
            android:textSize="28dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.043"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.406"/>
    
        <Button
            android:id="@+id/button_para1"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/watermelon"
            android:text="%"
            android:textColor="#060606"
            android:textSize="30dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.672"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.406" />
    
        <Button
            android:id="@+id/button_para2"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/watermelon"
            android:text="+/-"
            android:textColor="#060606"
            android:textSize="20dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.349"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.406" />
    
        <Button
            android:id="@+id/button_dot"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:backgroundTint="@color/pp"
            android:text="."
            android:textColor="@color/black"
            android:textSize="30dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.671"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.958" />
    
        <EditText
            android:id="@+id/input"
            android:layout_width="370dp"
            android:layout_height="92dp"
            android:hint=" ..."
            android:textAlignment="textEnd"
            android:textColor="@color/watermelon"
            android:textSize="50dp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.512"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.206" />
    
        <TextView
            android:id="@+id/output"
            android:layout_width="369dp"
            android:layout_height="83dp"
            android:textAlignment="textEnd"
            android:textColor="@color/clear"
            android:textSize="50dp"
            android:textStyle="bold"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.063" />
    
    </androidx.constraintlayout.widget.ConstraintLayout>
  ```
