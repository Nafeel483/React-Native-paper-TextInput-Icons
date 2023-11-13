# React-Native-Paper-TextInput-Icons-Names

Find All TextInput Icons of React-Native-Paper.

# Example as shown below.

# import { TextInput } from 'react-native-paper';
          
        <TextInput style={Styles.inputNameWrap}
          value={expiry}
          label="Expiry"
          placeholder={"Enter Expiry"}
          mode={"flat"}
          autoCapitalize="none"
          placeholderTextColor={Colors.lightGrey}
          textColor={Colors.White}
          underlineColor={Colors.lightGrey}
          activeUnderlineColor={Colors.lightGrey}
          onFocus={() => { pickDob() }}
          theme={{
            colors: {
              onSurfaceVariant: Colors.lightGrey
            },
          }} 
          right={<TextInput.Icon icon={"calendar-range-outline"} color={Colors.White}
          onPress={() => { pickDob() }} />}/>
