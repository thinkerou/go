# V1StatefulSetStatus

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CollisionCount** | **int32** | collisionCount is the count of hash collisions for the StatefulSet. The StatefulSet controller uses this field as a collision avoidance mechanism when it needs to create the name for the newest ControllerRevision. | [optional] 
**Conditions** | [**[]V1StatefulSetCondition**](v1.StatefulSetCondition.md) | Represents the latest available observations of a statefulset&#39;s current state. | [optional] 
**CurrentReplicas** | **int32** | currentReplicas is the number of Pods created by the StatefulSet controller from the StatefulSet version indicated by currentRevision. | [optional] 
**CurrentRevision** | **string** | currentRevision, if not empty, indicates the version of the StatefulSet used to generate Pods in the sequence [0,currentReplicas). | [optional] 
**ObservedGeneration** | **int64** | observedGeneration is the most recent generation observed for this StatefulSet. It corresponds to the StatefulSet&#39;s generation, which is updated on mutation by the API Server. | [optional] 
**ReadyReplicas** | **int32** | readyReplicas is the number of Pods created by the StatefulSet controller that have a Ready Condition. | [optional] 
**Replicas** | **int32** | replicas is the number of Pods created by the StatefulSet controller. | 
**UpdateRevision** | **string** | updateRevision, if not empty, indicates the version of the StatefulSet used to generate Pods in the sequence [replicas-updatedReplicas,replicas) | [optional] 
**UpdatedReplicas** | **int32** | updatedReplicas is the number of Pods created by the StatefulSet controller from the StatefulSet version indicated by updateRevision. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


