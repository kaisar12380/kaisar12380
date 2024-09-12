import react, {component} from 'react';
import {

StyleSheet,Text,View,StatusBar,TouchabOpacity
} from 'react-native';

import Logo from '../Component/Logo';
import Form from '../Commponent/Form';
import {Actions} from 'react-native-router-flux'

export default class Login extends Component <{}> {
signup(){
Action.signup()
}
render(){
return(
<View style = {style.container}>
<Logo/>
<Form type = "Login">
<View style = {style.signubTextCont}>
<Text style = {styles.sinupText}> Anda Belum Punya Akun ? </Text>
<TouchableOpacity onPress = {this.signub}>
<Text style = {styles.signubButton}> Signub </Text></TouchableOpacity>
</View></View>
)
}}
const style = StyleSheet.create({
container : {
backroundColor : '455a64', flex : 1,alignItem : 'center',
justifyContent : 'center'
},
signupTextCont : {
flexGrow : 1, alignItem : 'flex-end', justifyContent : 

