import { StatusBar } from 'expo-status-bar';
import { Image, StyleSheet, TextInput, TouchableOpacity, Text, View } from 'react-native';



export default function App() {
  return (
       
    <View style={styles.container}>
      
      <Image
        source={ { uri: 'https://sgedu.suportegerencial.com.br/login/assets/images/logo_sgedu.png'} }
        style={ styles.img }
      />
    <TextInput style={ styles.input }
    placeholder= "Nome"
    autoCorrect={false}
    onChangeText={()=> {}}
    />
    <TextInput style={ styles.input }
    placeholder= "Telefone"
    autoCorrect={false}
    onChangeText={()=> {}}  
    />
 <TouchableOpacity>
    <Text style={ styles.texto}>Entrar</Text>
 </TouchableOpacity> 
 <StatusBar style="auto" />

</View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#00008B',
    alignItems: 'center',
    justifyContent: 'center',
    color: 'black',
    marginBottom: 150,
  

  },
  texto: {
    color: 'blue',
    alignItems: 'center',
    justifyContent: 'center',
    fontSize: 20,
    marginTop: 50,
    backgroundColor:'red'
  },
  img: {
    marginTop: 20,
    marginBottom: 10,
    width: 350,
    height: 150
  },
  input:{
    backgroundColor:'#fff',
    width: '60%',
    marginBottom: 15,
    color: '#222',
    fontSize: 17,
    borderRadius: 10,
    padding: 10,

  }
});
