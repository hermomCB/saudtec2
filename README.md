# saudtec2

import { StyleSheet, View, Image } from "react-native";
import { Logo } from "../logo.png";

export  function Home() {
 return  <View style={styles.container}>
           <Image source={Logo} style={styles.logo}/>
         
         </View>
}

const styles = StyleSheet.create({
   container:{
    flex:1,
    backgroundColor:"#fff",
    alignItems: "center",
    
   },
});
