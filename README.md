# login-code
this is my code

<ScrollView>

        <Grid>

            <Grid.RowDefinitions>

                <RowDefinition Height="Auto"/>
                <RowDefinition Height="Auto"/>
                <RowDefinition Height="auto"/>

            </Grid.RowDefinitions>

            <Grid.ColumnDefinitions>

                <ColumnDefinition Width="385"/>

            </Grid.ColumnDefinitions>

            <skia:SKLottieView Source="lf20_nk5g0wbx.json" 
                                RepeatCount="-1"   Grid.Row="0" WidthRequest="300" 
                               HeightRequest="300">
            </skia:SKLottieView>

            <HorizontalStackLayout Grid.Row="1" Margin="45" HeightRequest="33">

                <Label Text="Login" FontSize="Title" FontAttributes="Bold" TextColor="#344663"/>

            </HorizontalStackLayout>

            <Grid Grid.Row="2" HorizontalOptions="Start" VerticalOptions="Center">

                <Grid.RowDefinitions>

                    <RowDefinition Height="Auto"/>
                    <RowDefinition Height="100"/>
                    <RowDefinition Height="Auto"/>
                    <RowDefinition Height="Auto"/>
                    <RowDefinition Height="Auto"/>
                    <RowDefinition Height="Auto"/>

                </Grid.RowDefinitions>

                <Grid.ColumnDefinitions>

                    <ColumnDefinition Width="450"/>
                    <ColumnDefinition Width="50"/>
                    <ColumnDefinition Width="Auto"/>
                    <ColumnDefinition Width="500"/>


                </Grid.ColumnDefinitions>

                <StackLayout Grid.Row="0" Grid.Column="0" Orientation="Horizontal" Margin="45,10,0,0" Spacing="10" HeightRequest="35">

                    <Image Source="userimgat2.svg" WidthRequest="20" VerticalOptions="Center"/>
                    <Entry Placeholder="Email" VerticalOptions="Center" WidthRequest="280" />

                </StackLayout>

                <StackLayout Grid.Row="1" Grid.Column="0" Orientation="Horizontal" Margin="45,0,0,0" Spacing="5">

                    <Image Source="lock.svg" WidthRequest="25" VerticalOptions="Center"/>
                    <Grid Grid.Column="1">

                        <Entry Placeholder="Password" VerticalOptions="Center" WidthRequest="280" />
                        <ImageButton Source="closeye2.svg" WidthRequest="35" HorizontalOptions="End"/>

                    </Grid>


                </StackLayout>

                <HorizontalStackLayout Grid.Row="2" HorizontalOptions="Start" Grid.Column="1" Margin="-210,-25,0,0">

                    <Label Text="Forgot password?" HorizontalOptions="Start" TextColor="#0065ff"/>

                </HorizontalStackLayout>

                <HorizontalStackLayout Grid.Row="3" Grid.Column="0" HorizontalOptions="Start" Margin="60,30,0,0">

                    <Button Text="Login" BackgroundColor="#0065ff" TextColor="Wheat" WidthRequest="300" x:Name="btnLogin" Clicked="btnLogin_Clicked"/>

                </HorizontalStackLayout>


                <StackLayout Orientation="Horizontal" Grid.Row="4" Grid.Column="2" Margin="-413,30,0,0">

                    <BoxView Grid.Column="0" Color="Gray" HeightRequest="1" WidthRequest="100"  VerticalOptions="Center" Margin="5" />

                    <Label Grid.Column="1" Text=" OR " HorizontalOptions="Center" VerticalOptions="Center" FontSize="14" TextColor="Black" />

                    <BoxView Grid.Column="2" Color="Gray" HeightRequest="1" WidthRequest="100"  VerticalOptions="Center" Margin="5" />

                </StackLayout>

                <StackLayout Orientation="Horizontal" Spacing="5" Grid.Row="5" HorizontalOptions="Center" Margin="-20,20,0,0">

                    <Label Text="New to logistic?"/>
                    <Label Text="Register" TextColor="#0065ff"/>

                </StackLayout>

            </Grid>

        </Grid>

    </ScrollView>
