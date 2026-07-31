# TrackWidgetEventRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventType** | **string** |  | 
**EntityId** | Pointer to **NullableInt32** |  | [optional] 
**EntityType** | Pointer to **NullableString** |  | [optional] 
**SourceDomain** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTrackWidgetEventRequest

`func NewTrackWidgetEventRequest(eventType string, ) *TrackWidgetEventRequest`

NewTrackWidgetEventRequest instantiates a new TrackWidgetEventRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackWidgetEventRequestWithDefaults

`func NewTrackWidgetEventRequestWithDefaults() *TrackWidgetEventRequest`

NewTrackWidgetEventRequestWithDefaults instantiates a new TrackWidgetEventRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventType

`func (o *TrackWidgetEventRequest) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *TrackWidgetEventRequest) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *TrackWidgetEventRequest) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetEntityId

`func (o *TrackWidgetEventRequest) GetEntityId() int32`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *TrackWidgetEventRequest) GetEntityIdOk() (*int32, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *TrackWidgetEventRequest) SetEntityId(v int32)`

SetEntityId sets EntityId field to given value.

### HasEntityId

`func (o *TrackWidgetEventRequest) HasEntityId() bool`

HasEntityId returns a boolean if a field has been set.

### SetEntityIdNil

`func (o *TrackWidgetEventRequest) SetEntityIdNil(b bool)`

 SetEntityIdNil sets the value for EntityId to be an explicit nil

### UnsetEntityId
`func (o *TrackWidgetEventRequest) UnsetEntityId()`

UnsetEntityId ensures that no value is present for EntityId, not even an explicit nil
### GetEntityType

`func (o *TrackWidgetEventRequest) GetEntityType() string`

GetEntityType returns the EntityType field if non-nil, zero value otherwise.

### GetEntityTypeOk

`func (o *TrackWidgetEventRequest) GetEntityTypeOk() (*string, bool)`

GetEntityTypeOk returns a tuple with the EntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityType

`func (o *TrackWidgetEventRequest) SetEntityType(v string)`

SetEntityType sets EntityType field to given value.

### HasEntityType

`func (o *TrackWidgetEventRequest) HasEntityType() bool`

HasEntityType returns a boolean if a field has been set.

### SetEntityTypeNil

`func (o *TrackWidgetEventRequest) SetEntityTypeNil(b bool)`

 SetEntityTypeNil sets the value for EntityType to be an explicit nil

### UnsetEntityType
`func (o *TrackWidgetEventRequest) UnsetEntityType()`

UnsetEntityType ensures that no value is present for EntityType, not even an explicit nil
### GetSourceDomain

`func (o *TrackWidgetEventRequest) GetSourceDomain() string`

GetSourceDomain returns the SourceDomain field if non-nil, zero value otherwise.

### GetSourceDomainOk

`func (o *TrackWidgetEventRequest) GetSourceDomainOk() (*string, bool)`

GetSourceDomainOk returns a tuple with the SourceDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceDomain

`func (o *TrackWidgetEventRequest) SetSourceDomain(v string)`

SetSourceDomain sets SourceDomain field to given value.

### HasSourceDomain

`func (o *TrackWidgetEventRequest) HasSourceDomain() bool`

HasSourceDomain returns a boolean if a field has been set.

### SetSourceDomainNil

`func (o *TrackWidgetEventRequest) SetSourceDomainNil(b bool)`

 SetSourceDomainNil sets the value for SourceDomain to be an explicit nil

### UnsetSourceDomain
`func (o *TrackWidgetEventRequest) UnsetSourceDomain()`

UnsetSourceDomain ensures that no value is present for SourceDomain, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


