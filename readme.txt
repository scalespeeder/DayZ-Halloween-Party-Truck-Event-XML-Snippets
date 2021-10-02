DAYZ Halloween Event Truck XML Snippets

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


XML Snippet to be added to your events.xml:

<event name="VehicleTruckEvent2">
        <nominal>1</nominal>
        <min>1</min>
        <max>1</max>
        <lifetime>300</lifetime>
        <restock>0</restock>
        <saferadius>500</saferadius>
        <distanceradius>500</distanceradius>
        <cleanupradius>200</cleanupradius>
        <flags deletable="0" init_random="0" remove_damaged="1"/>
        <position>fixed</position>
        <limit>mixed</limit>
        <active>1</active>
        <children>
            <!-- <child lootmax="0" lootmin="0" max="45" min="40" type="Truck_01_Covered"/> -->
            <child lootmax="0" lootmin="0" max="1" min="1" type="Truck_01_Covered_Blue"/> 
            <!-- <child lootmax="0" lootmin="0" max="1" min="1" type="Truck_01_Covered_Orange"/> -->
        </children>
		  </event>
		  
XML Snippet to be added to your cfgeventspawns.xml:

<event name="VehicleTruckEvent2">
		<pos x="359.60" z="3112.53" a="90.966431" /> <!--Truck will spawn at road juction North of Volchiypik -->
		 </event>
		 
XML Snippet to be added to your cfgspawnabletypes.xml, over the top of the existing Blue Truck entry:

<type name="Truck_01_Covered_Blue">
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Hood_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Door_1_1_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Door_2_1_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Barrel_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Barrel_Green" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Barrel_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Barrel_Yellow" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WoodenCrate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WoodenCrate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WoodenCrate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WoodenCrate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHat" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHat" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHat" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHat" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHat" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHat" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHood_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHood_Brown" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHood_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHood_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHood_Brown" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="WitchHood_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CrookedNose" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CrookedNose" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CrookedNose" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CrookedNose" chance="1.00" />
		</attachments>
			<attachments chance="1.00">
			<item name="CrookedNose" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CrookedNose" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CrookedNose" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CrookedNose" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SantasBeard" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SantasBeard" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SantasHat" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SantasHat" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_Flare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_Flare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareBlue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareBlue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareGreen" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareGreen" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareRed" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareRed" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_Flare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_Flare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareBlue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareBlue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareGreen" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareGreen" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareRed" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareRed" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Flaregun" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareBlue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareBlue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareGreen" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareGreen" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareRed" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ammo_FlareRed" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Flaregun" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Flaregun" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Flaregun" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Flaregun" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Roadflare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Roadflare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
		<item name="Roadflare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Roadflare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Roadflare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
		<item name="Roadflare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Roadflare" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_Green" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_Green" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_Purple" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_Purple" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_White" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_White" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_Yellow" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="M18SmokeGrenade_Yellow" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="PumpkinHelmet" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="PumpkinHelmet" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="PumpkinHelmet" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="PumpkinHelmet" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="PumpkinHelmet" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TireRepairKit" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="GreatHelm" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="PartyTent_Lunapark" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="PartyTent_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="PartyTent_Lunapark" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="PartyTent_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Vodka" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Vodka" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Vodka" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Megaphone" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Battery9V" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="FlashGrenade" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="FlashGrenade" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="FlashGrenade" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="FlashGrenade" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="FlashGrenade" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="FlashGrenade" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="FlashGrenade" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Chemlight_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Chemlight_Green" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Chemlight_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Chemlight_White" chance="1.00" />
		</attachments>
			<attachments chance="1.00">
			<item name="Chemlight_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Chemlight_Green" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Chemlight_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Chemlight_Yellow" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="XmasLights" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="XmasLights" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Battery9V" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Battery9V" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="XmasLights" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="XmasLights" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Battery9V" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Battery9V" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TacticalBaconCan_Opened" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TacticalBaconCan_Opened" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SodaCan_Pipsi" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SodaCan_Pipsi" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="ZagorkyChocolate" chance="1.00" />
		</attachments>
	</type>