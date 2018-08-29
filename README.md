# react-native-radio-lib

> Open your terminal or command prompt and install npm install react-native-radio-lib.

In computer science, this is known as an implementation of quasiquotes.

## Install

```sh
npm install --save react-native-radio-lib
```

## Usage

import {RadioButton, RadioGroup} from 'react-native-radio-lib';

## Example

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

