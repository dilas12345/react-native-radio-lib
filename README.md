#React native radio is created to ease some, stress feel free to use at your own pace.

#npm i react-native-radio-lib

#import {RadioButton, RadioGroup} from 'react-native-radio-lib';

###View example below###

	render(){
		return(
		<View >
                <RadioGroup style={{marginTop: 20}}
                    size={20}
                    thickness={1}
                    color='#222222'
                    onSelect = {(index, value) => this.onSelect(index, value)}
                >
                    <RadioButton value={'item1'} >
                        <Text style={{color: '#595959', fontSize: 15,fontFamily: 'Raleway-Regular'}}>Full Name + Expiry</Text>
                    </RadioButton>

                    <RadioButton value={'item2'}>
                        <Text style={{color: '#595959', fontSize: 15,fontFamily: 'Raleway-Regular'}}>Name + Expiry + DoB</Text>
                    </RadioButton>

                    <RadioButton value={'item3'}>
                        <Text style={{color: '#595959', fontSize: 15,fontFamily: 'Raleway-Regular'}}>Name + Nationality + Sex</Text>
                    </RadioButton>

                    <RadioButton value={'item3'}>
                        <Text style={{color: '#595959', fontSize: 15,fontFamily: 'Raleway-Regular'}}>Allow DoB Verification</Text>
                    </RadioButton>

                </RadioGroup>
              </View>
)
}

#Note

if there is any bug related to the module, please feel free pull a request so, it can be fixed

thanks 

Enjoy.
