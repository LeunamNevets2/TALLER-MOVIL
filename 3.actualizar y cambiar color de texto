package com.example.tallermovil
import android.os.Bundle
import androidx.activity.ComponentActivity
import androidx.activity.compose.setContent
import androidx.activity.enableEdgeToEdge
import androidx.compose.foundation.layout.fillMaxSize
import androidx.compose.foundation.layout.padding
import androidx.compose.material3.Scaffold
import androidx.compose.material3.Surface
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.tooling.preview.Preview
import com.example.tallermovil.ui.theme.TallerMovilTheme
import androidx.compose.ui.graphics.Color
import androidx.compose.material3.Text as Text1


class MainActivity : ComponentActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        enableEdgeToEdge()
        setContent {
            TallerMovilTheme {
                Scaffold(modifier = Modifier.fillMaxSize()) { innerPadding ->
                    Greeting(
                        name = "Android",
                        modifier = Modifier.padding(innerPadding)
                    )

                }
            }
        }
    }
}

@Composable
fun Greeting(name: String, modifier: Modifier = Modifier) {
    Text1(
        text = "Hello $name!",
        modifier = modifier
    )
}

@Composable
fun Greeting1(name: String) {
    Surface(color = Color.Magenta) {
        Text1(text = "Hi, my name is $name!")
    }
}

@Preview(showBackground = true)
@Composable
fun GreetingPreview() {
    TallerMovilTheme {
        Greeting("taller movil")
        Greeting1("manuel bejar")
    }
}
